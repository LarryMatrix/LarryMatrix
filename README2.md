### Hi there 👋 I'm Lawrance Massanja

![visitors](https://visitor-badge.laobi.icu/badge?page_id=LarryMatrix)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class DataEngineer:
    def __init__(self):
        self.name = "Lawrance Massanja"
        self.role = "Software Developer"
        self.location = "34.0522\xc2\xb0 N, 118.2437\xc2\xb0 W"
        self.blog = "https://github.com/LarryMatrix"
        self.knowledge_base = [
            "Software Enginnering",
            "Machine Learning",
            "Deep Learning",
            "Computer Vision",
            "Computer Programmer",
            "Data Analyst",
            "ANdroid and iOS App Developer"
        ]
        self.knowledge_base.insert(0, "Fullstack Engineering")

    def say_hi(self):
        print(
            """Hello my friend, thanks for dropping by!

This is {name}, I live in {location}. I work as a {role} and recently I am focusing on {focus} for my personal growth.

I have wide interests, but most of them are {knowledge_base}.

I write down tips and lecture notes on my personal tech blog, which can be found here: {blog}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                blog=self.blog,
            )
        )


me = DataEngineer()
me.say_hi()

```

## 🔧 Technologies & Tools

![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Golang-informational?style=flat&logo=go&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Kubernetes-informational?style=flat&logo=kubernetes&logoColor=white&color=6aa6f8)


<!--
**LarryMatrix/LarryMatrix** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
