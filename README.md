<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi!+👋;+I'm+Alina+Nikolaeva!;" />
</h1>

<div align="center">
  <img height="250" src="https://media1.tenor.com/m/u5uXD3icJ1kAAAAC/simpsons-homer-simpson.gif"  />
</div>

<h2 align="center">🦖I have skills:</h2>

<table width='100%' align="center">
  <tr>
    </td>
        <td align="center" width="110" height="90">
      <a href="#">
        <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" width="36" height="36" alt="Html5" />
      </a>
      <br>Html5
    </td>
         <td align="center" width="110" height="90"> 
      <a href="#" >
        <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-original.svg" width="36" height="36" alt="css3" />
      </a>
      <br>Css3
    </td>
     <td align="center" width="110" height="90"> 
      <a href="#" >
        <img src="https://techstack-generator.vercel.app/github-icon.svg" width="65" height="65" alt="github" />
      </a>
      <br>github
    </td>
    <td align="center" width="110" height="90"> 
      <a href="#" >
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40" height="40" alt="vscode" />
      </a>
      <br>vscode
    </td>
      </a>
    </td>
  </tr> 
</table>

<h3>
<details>
  <summary>GitHub Stats</summary>
  <table align="center">
   <tr>
      <td><img alt="github stats" width="550px" align="left" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Exremum&theme=solarized_dark" /></td>
      <td><img alt="github stats" width="750px" src="https://github-readme-stats.vercel.app/api/top-langs?username=Exremum&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false&order=2" /></td>
   </tr>
  </table>
  <p align="center"><img alt="github streak" width="420" src="https://streak-stats.demolab.com/?user=Exremum&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3"></p>
</details>
</h3>

###

<div align="center">
  <img src="https://visitcount.itsvg.in/api?id=Exremum&label=Profile%20Views&color=1&icon=0&pretty=true"  />
</div>

###


- uses: Exremum/Exremum
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
