<!-- Introduction -->
<h1> Hi 👋  Welcome to my Github profile.</h1>

      I'm Letícia Merink and I'm 34 years old.
      I love technology and how it can transform people's lives.
      Because this, I'm computing, science, innovation and tech lover.

- 🌱 I’m currently learning <strong>Java, Python, MySQL, Power BI and Scrum</strong>
- 🎓 Graduating in Systems Analysis and Development at [Fatec Guaratinguetá](http://www.fatecguaratingueta.edu.br/).
- 📚 Studying to be the best data analyst and back end developer I can be.
- 🙋🏻 Available and looking for an internship in software development.

<br>
<!-- GitHub Infos -->

## ⚙️ &nbsp;GitHub Analytics
<p align="left">
<img width="395em" src="https://github-readme-stats.vercel.app/api?username=lucassb15&show_icons=true&theme=vision-friendly-dark" alt="lucassb15's stats"/>
<img width="395em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucassb15&layout=compact&theme=vision-friendly-dark" alt="lucassb15's most languages"/>
</p>

<br>
 <!-- Tools -->
 
 ## 🛠 &nbsp;Tech Stack.

![Java](	https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)&nbsp;
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)&nbsp;
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)&nbsp;
![Git](https://img.shields.io/badge/Git-E34F26?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;

<br>
<!-- Social network -->

## 👱‍♀️ &nbsp;Social Links

<p align="left" style="background:yellow">
<a href="https://www.linkedin.com/in/let%C3%ADcia-merink-b36687227/" target="_blank">
  <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
</a>
<a href="https://www.instagram.com/leticiamohring/" target="_blank">
 <img align="center" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=leticiamohring&logoColor=white" alt="instagram"/>
name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: WagnerSousaLima
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
      </a>
</p>

