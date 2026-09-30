<!-- HEADER: solid gradient background => white name is readable in BOTH light and dark mode -->
![header](https://capsule-render.vercel.app/api?type=waving&color=0:6a0dad,50:a855f7,100:06b6d4&height=240&section=header&text=Harshad%20Dhonde&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Engineer%20%C2%B7%20AI%20%26%20RAG%20Builder&descSize=20&descAlignY=58&descColor=ffffff)

<div align="center">

<!-- Typing SVG: theme-aware colours -->
<a href="https://git.io/typing-svg">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=C084FC&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+Engineer+%F0%9F%9A%80;AI+%26+RAG+Pipeline+Builder+%F0%9F%A4%96;Spring+Boot+%7C+React+%7C+LangChain+%7C+JWT;Open+to+Internships+%26+Collaborations!">
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=6D28D9&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+Engineer+%F0%9F%9A%80;AI+%26+RAG+Pipeline+Builder+%F0%9F%A4%96;Spring+Boot+%7C+React+%7C+LangChain+%7C+JWT;Open+to+Internships+%26+Collaborations!">
    <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&height=50&lines=Full-Stack+Engineer+%F0%9F%9A%80;AI+%26+RAG+Pipeline+Builder+%F0%9F%A4%96;Spring+Boot+%7C+React+%7C+LangChain+%7C+JWT;Open+to+Internships+%26+Collaborations!">
  </picture>
</a>

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhondeharshad4@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshaddhonde4)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshaddhonde4)

![Profile Views](https://komarev.com/ghpvc/?username=harshaddhonde4&label=Profile+Views&color=a855f7&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/harshaddhonde4?label=Followers&style=for-the-badge&color=06b6d4)

</div>

---

## 👨‍💻 About Me

I'm a **full-stack developer from Pune** who loves turning ideas into secure, production-style applications, and building **AI apps that never leave your machine**.

| | |
|:--|:--|
| 🎯 **Focus** | Full-Stack Web Development · AI / RAG Pipeline Engineering · Secure Backends (JWT + Spring Security + RBAC) |
| 🔭 **Exploring** | Microservices & Docker · System Design & Scalability · Cloud (AWS) |
| 📍 **Location** | Pune, Maharashtra, India |
| 🤝 **Open to** | Internships & Collaborations |
| ⚡ **Fun fact** | My LLM apps run 100% on-device: no API keys, no data leakage |

---

## 🛠️ Tech Arsenal

<div align="center">

**⚙️ Backend**<br/>
![Backend](https://skillicons.dev/icons?i=java,spring,hibernate,maven)

**🎨 Frontend**<br/>
![Frontend](https://skillicons.dev/icons?i=react,redux,javascript,html,css,tailwind)

**🤖 AI / ML**<br/>
![AI](https://skillicons.dev/icons?i=python)<br/>
`LangChain` · `Ollama (Llama 3.2)` · `ChromaDB` · `Google Gemini API` · `RAG Pipelines`

**🗄️ Databases**<br/>
![Databases](https://skillicons.dev/icons?i=mysql,mongodb)

**🔧 Tools & Platforms**<br/>
![Tools](https://skillicons.dev/icons?i=git,github,vscode,idea,aws,linux)

</div>

---

## 🚀 Featured Projects

| 🔖 Project | 💡 Description | ⚡ Stack | 🔗 |
|:---|:---|:---|:---:|
| 🦙 **LlamaLocal + RAG** | Privacy-first RAG: chat with any webpage using an on-device LLM. Zero API keys, zero data leakage | Python · LangChain · Ollama · ChromaDB · Streamlit | [![repo](https://img.shields.io/badge/-Repo-171515?style=flat&logo=github)](https://github.com/harshaddhonde4) |
| 🛒 **StickyVibe** | Full-stack e-commerce with Stripe payments, JWT auth and a Redux SPA | React · Redux · Spring Boot · JWT · MySQL · Stripe | [![repo](https://img.shields.io/badge/-Repo-171515?style=flat&logo=github)](https://github.com/harshaddhonde4) |
| 🏫 **EazySchool** | School ERP with 3-tier RBAC for students, teachers and admins | Spring Boot · Thymeleaf · Spring Security · MySQL | [![repo](https://img.shields.io/badge/-Repo-171515?style=flat&logo=github)](https://github.com/harshaddhonde4/EazySchool-Web-Application) |
| 🌾 **Smart Crop Advisory** | AI farming platform using Google Gemini for crop and irrigation advice | Spring Boot · Gemini API · Java · Thymeleaf | [![repo](https://img.shields.io/badge/-Repo-171515?style=flat&logo=github)](https://github.com/harshaddhonde4/Smart-Crop-Advisory-System) |

### 🦙 LlamaLocal RAG: How it works

```mermaid
flowchart TD
    A[🌐 User enters URL] --> B[Webpage Fetcher<br/>LangChain Document Loader]
    B --> C[Chunk Splitter<br/>500 chars · 50 overlap]
    C --> D[OllamaEmbeddings<br/>local vector generation]
    D --> E[(ChromaDB<br/>per-URL isolated collection)]
    E --> F[Similarity Search<br/>top-k chunks]
    F --> G[🦙 Llama 3.2 via Ollama<br/>on-device inference]
    G --> H[💬 Streamlit UI<br/>persistent chat history]
```

---

## 📊 GitHub Stats

<div align="center">

<!-- Stats card -->
<a href="https://github.com/harshaddhonde4">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=harshaddhonde4&show_icons=true&hide_border=true&bg_color=0d1117&title_color=c084fc&icon_color=22d3ee&text_color=c9d1d9&count_private=true">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=harshaddhonde4&show_icons=true&hide_border=false&border_color=e2e8f0&bg_color=ffffff&title_color=6d28d9&icon_color=0891b2&text_color=334155&count_private=true">
    <img alt="Harshad's GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=harshaddhonde4&show_icons=true&hide_border=true&bg_color=0d1117&title_color=c084fc&icon_color=22d3ee&text_color=c9d1d9&count_private=true">
  </picture>
</a>

<!-- Streak -->
<a href="https://git.io/streak-stats">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=harshaddhonde4&hide_border=true&background=0d1117&stroke=a855f7&ring=a855f7&fire=f97316&currStreakLabel=c084fc&currStreakNum=c9d1d9&sideNums=c9d1d9&sideLabels=94a3b8&dates=64748b">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=harshaddhonde4&hide_border=false&border=e2e8f0&background=ffffff&stroke=e2e8f0&ring=6d28d9&fire=f97316&currStreakLabel=6d28d9&currStreakNum=334155&sideNums=334155&sideLabels=475569&dates=64748b">
    <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=harshaddhonde4&hide_border=true&background=0d1117&stroke=a855f7&ring=a855f7&fire=f97316&currStreakLabel=c084fc&currStreakNum=c9d1d9&sideNums=c9d1d9&sideLabels=94a3b8&dates=64748b">
  </picture>
</a>

<!-- Top languages -->
<a href="https://github.com/harshaddhonde4">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=harshaddhonde4&layout=compact&hide_border=true&bg_color=0d1117&title_color=c084fc&text_color=c9d1d9&langs_count=8">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=harshaddhonde4&layout=compact&hide_border=false&border_color=e2e8f0&bg_color=ffffff&title_color=6d28d9&text_color=334155&langs_count=8">
    <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshaddhonde4&layout=compact&hide_border=true&bg_color=0d1117&title_color=c084fc&text_color=c9d1d9&langs_count=8">
  </picture>
</a>

</div>

---

## 📈 Contribution Activity

<div align="center">

<a href="https://github.com/ashutosh00710/github-readme-activity-graph">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=harshaddhonde4&bg_color=0d1117&color=c084fc&line=22d3ee&point=ffffff&area=true&hide_border=true">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=harshaddhonde4&bg_color=ffffff&color=6d28d9&line=0891b2&point=334155&area=true&hide_border=true">
    <img alt="Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=harshaddhonde4&bg_color=0d1117&color=c084fc&line=22d3ee&point=ffffff&area=true&hide_border=true">
  </picture>
</a>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harshaddhonde4/harshaddhonde4/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/harshaddhonde4/harshaddhonde4/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/harshaddhonde4/harshaddhonde4/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

---

## 🤝 Let's Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhondeharshad4@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshaddhonde4)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshaddhonde4)

*"The best way to predict the future is to build it."*

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:a855f7,100:6a0dad&height=120&section=footer)
