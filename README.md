### Hi there, Eu sou o Matheus Fortes!



- 🔭  Estou estudando Frontend.
- 🌱 I’m currently lear  HTML e CSS.
- 😄 Pronouns:  ele/dele.

 <div>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=MatheusFortes20&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
  
  ##
 
<div> 
 
  <a href="https://instagram.com/matheus___fortes" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/matheus-fortes-403711212" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 


</div>
- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
