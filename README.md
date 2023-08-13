<img src="https://github.com/clementpoiret/clementpoiret/blob/master/header.png" />

```python
class AboutMe:
    """
    Hey, I'm Clément, a Linux power-user, with a Ph.D. in neurosciences.
    I'm a tech enthusiast, I like scripting and automating everything,
    I love open source, and open science. I write papers on AI.

    Previously worked in: Android Reverse Engineering (SMALI),
                          Neuroinformatics.
    Currently working in: AI (Computer Vision).
    """

    def __init__(self):
        self.is_phd: bool = True
        self.phd_fields: List[str] = ["neurosciences", "deep learning"]

    def get_expertise(self) -> Dict[List[str]]:
        return {
            "fields": [
                "machine and deep learning",
                "neurosciences",
                "web development",
                "native development",
                "devops",
                "sysadmin",
                "reverse engineering"
            ],
            "tools": [
                "pytorch", "tensorflow", "archlinux", "vim", "kitty", "zsh"
            ],
            "languages": [
                "python", "(java/type)script", "julia", "dart", "html", "css", "smali", "lua"
            ]
        }

    def get_interests(self) -> List[str]:
        return [
            "learning new skills everyday",
            "conducting scientific experiments",
            "tweaking my linux distro",
            "dismantling computers",
            "philosophy (hi, Nietzsche!)"
        ]

    def get_future_goals(self) -> str:
        return "Develop expertise in Quantum Computing, and QML."
```

---

### 📫 Come say hi!

[![GitHub][GithubBadge]][GithubUrl]
[![Twitter][TwitterBadge]][TwitterUrl]
[![LinkedIn][LinkedinBadge]][LinkedinUrl]

[GithubBadge]: https://img.shields.io/badge/collaborate-github-171515?logo=github&logoColor=ffffff
[TwitterBadge]: https://img.shields.io/badge/follow-twitter-1da1f2?logo=twitter&logoColor=ffffff
[LinkedinBadge]: https://img.shields.io/badge/connect-LinkedIn-0a66c2?logo=linkedin&logoColor=ffffff

[GithubUrl]: https://github.com/clementpoiret
[TwitterUrl]: https://x.com/clement_poiret1
[LinkedinUrl]: https://linkedin.com/in/clement-poiret
