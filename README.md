<h1 align=center>📚 Daehyuh318`s Stacks 📚</h1>

<div align=center> 
  <br>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
   <img src="https://img.shields.io/badge/autohotkey-334455?style=for-the-badge&logo=autohotkey&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
    <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
  <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white"> 
  <br>
  <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"> 
  <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> 
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">  
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <br><br>
    
![daehyuh318's GitHub stats](https://github-readme-stats.vercel.app/api?username=daehyuh318&show_icons=true&theme=gruvbox)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=daehyuh318&layout=compact)](https://github.com/daehyuh318/)   
  <br>
</div>

<h1 align=center>📚 Daehyuh318`s Projects 📚</h1>

<div align=center>
<br>

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=PatrascheProject)](https://github.com/daehyuh318/PatrascheProject)<br>
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=ZedProject)](https://github.com/daehyuh318/ZedProject)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=LidarProject)](https://github.com/daehyuh318/LidarProject)<br>
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=TrafficLightProject)](https://github.com/daehyuh318/TrafficLightProject)<br>
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=University-API)](https://github.com/daehyuh318/University-API)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=daehyuh318&repo=Self-Check-Macro)](https://github.com/daehyuh318/Self-Check-Macro)<br>

<br>
</div>

<h1 align=center>🤪I'm manipulating the hits, Just for fun !🤪</h1>

<br>

```python
import requests
from bs4 import BeautifulSoup as bs

status = ""
user = "daehyuh318"
repo = "daehyuh318"
fullurl = user + "%2F" + repo

while True:
    try:
        page = requests.get(
            "https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F" + fullurl)
        soup = bs(page.text, "html.parser")
        pry = soup.find_all("text")[3].string
        if status != pry:
          print(pry)
          status = pry
    except:
        pass
```

<br>

<div align=center>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdaehyuh318%2Fdaehyuh318&count_bg=%23B4B4B4&title_bg=%23555555&icon=ghostery.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

