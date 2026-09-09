<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Roboto&weight=700&size=35&duration=4000&pause=1000&color=FFF7EF&background=00000000&center=true&vCenter=true&width=900&height=70&lines=Hi%2C+I'm+Ansh+Rajput+👋;B.Tech+CSE+(AI)+Student;Full+Stack+Developer+%7C+AI+Enthusiast+🚀">
</h1>

<img align="right" alt="PC GIF" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/PC.gif" width="190" />

### Hey <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="29px">,

<p>
  <em>
    I am a <b>B.Tech student in Computer Science (AI)</b> from India 🇮🇳.
    I am passionate about <b>Full Stack Development</b> and <b>Artificial Intelligence</b>.
    I love solving problems using <b>DSA in C++</b> and building real-world web applications.
  </em>
</p>

- 🔭 I’m currently working on **Full Stack Projects**
- 🌱 I’m currently learning **MERN Stack & AI Integration**
- 💬 Ask me about **C++, DSA, Web Development**
- 📫 How to reach me **(Add your LinkedIn here)**

---

<h2 align="center">Languages, Frameworks and Tools:</h2>

<div align="center">
<img src="https://skillicons.dev/icons?i=cpp,html,css,js,react,nodejs,express,mongodb,mysql,git,github,vscode,figma,bootstrap,tailwind,postman,linux&perline=9" />
</div>

---

### 📊 GitHub Stats



<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=anshrajput277-prog&theme=tokyonight" />
</p>



---

<div align="center">
  name: generate animation

on:
  schedule:
    - cron: "0 */6 * * *"   # har 6 ghante mein refresh
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions: 
      contents: write
    steps:
      - uses: actions/checkout@v4
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk@v3
        with:
          github_user_name: anshrajput277-prog
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</div>

---

### 🤝 Connect with me

| LinkedIn | GitHub |
|--------|--------|
| www.linkedin.com/in/ansh-rajput-6a42a2328 | https://github.com/anshrajput277-prog |
