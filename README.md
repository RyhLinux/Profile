Opa fi, bão?

<img  height="180em" src="https://github-readme-stats.vercel.app/api?username=RyhLinux&show_icons=true&theme=great-gatsby&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RyhLinux&layout=compact&langs_count=16&theme=great-gatsby"/>
</div>
<br>


<div  align="center"> 
  <div style="display: inline_block"><br>
    <img align="left" height="250" alt="coding-time" src="code.gif">
    <h1 align="center"> 𝚃𝚎𝚌𝚗𝚘𝚕𝚘𝚐𝚒𝚊𝚜 </h1>
    <img align="center" height="30" width="40" alt="RyhLinux-js-icon"  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
    <img align="center" height="30" width="40" alt="RyhLinuxx-react-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
    <img align="center" height="30" width="40" alt="RyhLinux-html-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
    <img align="center" height="30" width="40" alt="RyhLinux-css-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
    <img align="center" height="30" width="40" alt="RyhLinux-c-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">
    <img align="center" height="30" width="40" alt="RyhLinux-nodejs-icon" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
    <img align="center" height="30" width="40" alt="RyhLinux-nodejs-icon" src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/cpp.svg">
    
    
 <div  align="center"> 
  <div style="display: inline_block"><br>
    <img align="left" height="250" alt="coding-time" src="code.gif">
    <img alifn="center" height="30" width="40" alt="RyhLinux-linux-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" />
    <img alifn="center" height="30" width="40" alt="RyhLinux-python-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
    <img alifn="center" height="30" width="40" alt="RyhLinux-pyscript-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pyscript/pyscript-original-wordmark.svg" />
    <img alifn="center" height="30" width="40" alt="RyhLinux-linkedin-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" />
    <img alifn="center" height="30" width="40" alt="RyhLinux-lua-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/lua/lua-original.svg" />  
    <img alifn="center" height="30" width="40" alt="RyhLinux-latex-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/latex/latex-original.svg" /> 




𝙼𝚢 𝚠𝚘𝚛𝚕𝚍


<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

**github action**

```yaml
- uses: Platane/snk@v3
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
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)


