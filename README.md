### Hi there 👋

<!--
**hdalarme/hdalarme** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
<details open>
    <summary>⚙ <b>GitHub Analytics</b>: </summary>
    <br>
    <p align="center">
        <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=hdalarme&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
        <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=hdalarme&layout=compact&langs_count=8&theme=tokyonight&include_all_commits=true&count_private=true"/> 
    </p>

![Snake animation](https://github.com/hdalarme/hdalarme/blob/output/github-contribution-grid-snake.svg)
    
- uses: hdalarme/hdalarme@v2
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

</details>
