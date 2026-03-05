<!-- HEADER -->
<h1 align="center">Hi 👋 I'm Hanine Boudour</h1>
<h3 align="center">Software Engineer • Full Stack Developer • AI & AR Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=900&color=00C2FF&center=true&vCenter=true&width=850&lines=Software+Engineer;Full+Stack+Developer;AI+%26+AR+Explorer;3D+Chatbot+Developer;UI%2FUX+Designer+%26+3D+Creator;Always+Learning+New+Things" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HanineBDR&style=for-the-badge" />
</p>

---

## 👩‍💻 About Me

```diff
+ Software Engineering Student
+ Passionate about Web Development, AI and AR technologies
+ Built 3D + AR chatbot experiences
+ UI/UX Designer and 3D creator (Canva • Figma • Blender)
```

-   🌍 Based in **Constantine, Algeria**
-   🔗 Portfolio: https://haninebd.github.io/portfolio/
-   💼 LinkedIn: https://www.linkedin.com/in/hanine-boudour-9a7474397
-   📫 Email: hanine.boudour@univ-constantine2.dz

------------------------------------------------------------------------

## 🚀 Tech Stack

### 💻 Programming & Development

```{=html}
<p align="center">
```
`<img src="https://skillicons.dev/icons?i=html,css,tailwind,js,react,java,spring,mysql,git,github&perline=10" />`{=html}
```{=html}
</p>
```
### 🎨 Design & 3D Tools

```{=html}
<p align="center">
```
`<img src="https://skillicons.dev/icons?i=figma,blender&perline=10" />`{=html}
`<img src="https://cdn.simpleicons.org/canva/00C2FF" height="48" alt="Canva"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 📊 GitHub Stats

```{=html}
<p align="center">
```
`<img src="https://github-readme-stats.vercel.app/api?username=HanineBDR&show_icons=true&theme=tokyonight&hide_border=true"/>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<img src="https://streak-stats.demolab.com?user=HanineBDR&theme=tokyonight&hide_border=true"/>`{=html}
```{=html}
</p>
```
```{=html}
<p align="center">
```
`<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HanineBDR&layout=compact&theme=tokyonight&hide_border=true"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 🏆 GitHub Trophies

```{=html}
<p align="center">
```
`<img src="https://github-profile-trophy.vercel.app/?username=HanineBDR&theme=tokyonight&no-frame=true&row=1&column=7"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 📈 Activity Graph

```{=html}
<p align="center">
```
`<img src="https://github-readme-activity-graph.vercel.app/graph?username=HanineBDR&theme=tokyo-night&hide_border=true"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 🐍 Contribution Snake Animation

```{=html}
<p align="center">
```
`<img src="https://raw.githubusercontent.com/HanineBDR/HanineBDR/output/github-contribution-grid-snake.svg"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 🌐 Connect With Me

```{=html}
<p align="center">
```
`<a href="https://www.linkedin.com/in/hanine-boudour-9a7474397">`{=html}
`<img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin"/>`{=html}
`</a>`{=html}

`<a href="https://haninebd.github.io/portfolio/">`{=html}
`<img src="https://img.shields.io/badge/Portfolio-black?style=for-the-badge&logo=firefoxbrowser"/>`{=html}
`</a>`{=html}

`<a href="mailto:hanine.boudour@univ-constantine2.dz">`{=html}
`<img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail"/>`{=html}
`</a>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## 💡 Quote

> "Technology is best when it brings creativity and innovation
> together."

⭐ From **Hanine Boudour**


    ---

    # 2️⃣ Snake Animation Workflow

    Create the file:

    `.github/workflows/snake.yml`

    ```yaml
    name: Generate Snake

    on:
      schedule:
        - cron: "0 0 * * *"
      workflow_dispatch:

    permissions:
      contents: write

    jobs:
      build:
        runs-on: ubuntu-latest
        steps:
          - name: Generate snake SVG
            uses: Platane/snk/svg-only@v3
            with:
              github_user_name: HanineBDR
              outputs: |
                dist/github-contribution-grid-snake.svg

          - name: Push snake to output branch
            uses: crazy-max/ghaction-github-pages@v4
            with:
              target_branch: output
              build_dir: dist
            env:
              GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
