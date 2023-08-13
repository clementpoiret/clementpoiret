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

<div>
  <a href="https://github.com/clementpoiret" target="_blank">
    <img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/clement-poiret" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" />
  </a>
</div>
