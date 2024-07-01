# Hi there 👋

<!-- 🧑🏼‍🎓 I'm a Franco-American double-degree student at [NTNU](https://www.ntnu.edu/studies/msit) (Norwegian University of Science and Technologies) in the Master of Science in Informatics specializing in artificial intelligence. I come from a preparatory class (French education system) which enabled me to enter the [Ecole Centrale de Nantes](https://www.ec-nantes.fr/) after the competitive entrance exam.  -->

<!-- 🌱 I then try to share on this profile, my projects carried out as part of my studies, but also those carried out for my personal interest, mixing the fields in which I have a particular interest. -->

```python
from typing import Tuple, List, Dict


class TestStack:
    pass

class Attributes(TestStack):
    @property
    def contact(self) -> Tuple[str, Dict[str, str]]:
        linkedin = "/in/arthur-testard/"
        emails   = { 
            "personal": "testardarthur@gmail.com",
            "ecn"     : "arthur.testard@eleves.ec-nantes.fr",
            "ntnu"    : "ajtestar@stud.ntnu.no",
        }

        return linkedin, emails

    @property
    def life(self) -> Tuple[List[str], Dict[str, str], int, List[str]]:
        ids      = ["French", "American"]
        langs    = {
            "French"  : "Native",
            "English" : "Fluent",
            "Japanese": "Beginner",
        }
        age      = 25
        passions = ["mathematics", "informatic", "physic", "cello", "hikes"]

        return ids, langs, age, passions

    @property
    def experiences(self) -> Tuple[Dict[str, Dict[str, str]], Dict[str, Dict[str, str]]]:
        """More information on my linkedIn"""
        studies = {
            "ntnu": {
                "univ"  : "Norwegian University of Science and Technology",
                "dates" : "2023-2025",
                "degree": "master",
                "spe"   : "artificial intelligence"
                "loc"   : "no"
            },
            "ecn": {
                "univ"  : "Ecole Centrale de Nantes",
                "dates" : "2020-2025",
                "degree": "master",
                "spe"   : "general engineering",
                "loc"   : "fr"
            }
        }
        jobs    = {
            "rokken": {
                "firm"  : "@Rokken-lab6",
                "dates" : "2022/11-2023/05",
                "role"  : "machine learning engineer intern",
                "loc"   : "jp",
            },
            "padoa": {
                "firm"  : "@padoa",
                "dates" : "2022/04-2022/08",
                "role"  : "fullstack developer intern",
                "loc"   : "fr"
            },
        }

        return studies, jobs

    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'good'    : ['python'],
            'medium'  : ['ts', 'js'],
            'learning': ['c', 'c++']
        }
        prefs = ['ai', 'fullstack']
        ide   = ['vscode', 'pycharm', 'webstorm']
        pc    = {
            'MacOS': {
                'macbook pro m2': {
                    'processor': 'm2 | 8 cores',
                    'ram'      : '16gb',
                    'gpu'      : 'm2 | 8 cores'
                }
            },
        }

        return langs, prefs, ide, pc
```
Template found here[^1].

# 💬 Contact

<p align="center">
	<a href="https://www.linkedin.com/in/arthur-testard/">
		<img src="https://img.shields.io/badge/-LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
	</a>
	<span>&nbsp;</span>
	<a href="mailto:testardarthur@gmail.com">
		<img src="https://img.shields.io/badge/-GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white">
	</a>
</p>

# 💻 Skills:

## 🗣️ Languages
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,c,cs,cpp,js,ts,css,html,matlab,bash" />
  </a>
</p>

## 📦 Packages/Libraries/Frameworks
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,fastapi,django,flask" />
	<!-- add keras, matplotlib, pandas,numpy-->
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
	<img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white"/>
	<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib"/>
	<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
	<img src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white"/>
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=npm,yarn,react,nextjs,nodejs" 
	/>
  </a>
</p>

## 🔨 Tools


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=apple,linux,ubuntu,windows" 
	/>
  </a>
</p>


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,stackoverflow,docker,postgres,sqlite,azure,firebase,tailwind,latex," 
	/>
  </a>
</p>

<p align="center">
  <a href="">
    <img src="https://img.shields.io/badge/CIRCLECI-02303A.svg?style=for-the-badge&logo=CIRCLECI&logoColor=white&color=%23343434" 
	/>
  </a>
</p>


# 📊 GitHub Stats:

<p href="" align="center">
    <img alt="" src="
		https://github-readme-stats.vercel.app/api?username=art-test-stack&theme=tokyonight&show_icons=true&locale=en">
</p>

<!-- <p href="" align="center">
    <img alt="" src="
		https://github-readme-streak-stats.herokuapp.com/?user=art-test-stack&theme=tokyonight&">
</p> -->


<p href="https://git.io/streak-stats" align="center">
    <img alt="" src="
		https://streak-stats.demolab.com?user=art-test-stack&theme=tokyonight&hide_border=false">
</p>

<!-- [![GitHub Streak]()]() -->

<p href="" align="center">
    <img alt="" src="
		https://github-readme-stats.vercel.app/api/top-langs?username=art-test-stack&theme=tokyonight&show_icons=true&locale=en">
</p>


# 🏆 GitHub Trophies

<p href="" align="center">
    <img alt="" src="
		https://github-profile-trophy.vercel.app/?username=art-test-stack&theme=tokyonight">
</p>


# ✍️ Random Dev Quote

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

# ☕️ Support:

<p href="https://www.buymeacoffee.com/artestack"> 
	<img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="artestack" />
</p>

<!-- <p href="" align="left">
	<img alt="" src="https://visitcount.itsvg.in/api?id=art-test-stack&icon=0&color=0)](https://visitcount.itsvg.in"/>
</p> -->

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

# 📚 References

[^1]: https://github.com/xtekky/xtekky/blob/main/README.md?plain=1