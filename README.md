### Olá, eu sou Luiz Henrique Siqueira!

- 📕 Estudante de Análises e Desenvolvimento de Sistemas.
- 💻 Desenvolvedor Web Jr.
- 🧔🏻 Pronome: ele/dele.
- 📩 Email: lhlsiqueira@gmail.com

##

<div>
  <a href="https://github.com/luizhenriquesiqueira">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=luizhenriquesiqueira&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luizhenriquesiqueira&layout=compact&langs_count=7&theme=dark"/>
</div>



  

<div style="display: inline_block"><br>
  <img align="center" alt="luiz-Js" height="60" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="luiz-HTML" height="60" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="luiz-CSS" height="60" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="luiz-PHP" height="60" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg">
  
  
  <br> <br>
  
  <div>
    <a href="https://www.linkedin.com/in/luiz-henrique-lima-a45431202/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
     <a href="https://instagram.com/luizhe" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
    

  </div>
  
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
          github_user_name: luizhenriquesiqueira
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ##
  
 
</div>
