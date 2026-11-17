<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0D1117,50:0969DA,100:8250DF&text=Mohamed%20Yousuf%20S&fontColor=FFFFFF&fontSize=46&fontAlignY=36&desc=Generative%20AI%20Engineer%20%E2%80%A2%20Full-Stack%20Developer&descAlignY=57&descSize=17&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2600&pause=900&color=58A6FF&center=true&vCenter=true&repeat=true&width=760&lines=Engineering+LLM+%2B+RAG+powered+products;Designing+AI+agents+that+act%2C+not+just+chat;From+prompt+to+production%2C+end+to+end;Python+%E2%80%A2+React+%E2%80%A2+Node.js+%E2%80%A2+PostgreSQL)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yousufmohameds)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedyousufs.tech@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YousufS09)

![Location](https://img.shields.io/badge/Chennai-India-0969DA?style=flat-square&logo=googlemaps&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-LLMs_%7C_RAG_%7C_AI_Agents-8250DF?style=flat-square)
![Profile Views](https://komarev.com/ghpvc/?username=YousufS09&label=Profile+views&color=0969DA&style=flat-square)

<br>

**I design and ship AI-powered products end to end** - from retrieval pipelines and autonomous agents<br>
to the interfaces and APIs that put them in people's hands.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/terminal-intro.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/terminal-intro-light.svg" />
  <img width="100%" alt="Animated terminal: whoami and profile.json showing mission, focus areas, stack and what I am exploring" src="./assets/terminal-intro.svg" />
</picture>

</div>

## How I build

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/engineering-flow.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/engineering-flow-light.svg" />
  <img width="100%" alt="Animated AI application pipeline: interface, API, retrieval, reasoning, persistence" src="./assets/engineering-flow.svg" />
</picture>

</div>

<table>
  <tr>
    <td width="33%" valign="top" align="center">
      <h4>Grounded AI</h4>
      <sub>Retrieval-augmented answers, structured outputs and deterministic fallbacks - not just a raw model call.</sub>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>Production-minded</h4>
      <sub>Verified webhooks, validation, rate limiting and centralized error handling from day one.</sub>
    </td>
    <td width="33%" valign="top" align="center">
      <h4>Product-first</h4>
      <sub>Clean interfaces and end-to-end ownership, so intelligent features feel effortless to use.</sub>
    </td>
  </tr>
</table>

## Featured work

<div align="center">

<a href="https://github.com/YousufS09/code-review-ai-agent">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/project-code-review.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/project-code-review-light.svg" />
  <img width="100%" alt="Code Review AI Agent: an autonomous reviewer that reads every pull request and responds with actionable findings" src="./assets/project-code-review.svg" />
</picture>
</a>

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/YousufS09/resume_parser_fe">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/project-resume-intelligence.svg" />
          <source media="(prefers-color-scheme: light)" srcset="./assets/project-resume-intelligence-light.svg" />
          <img width="100%" alt="Resume Intelligence: turns unstructured resumes into searchable candidate intelligence" src="./assets/project-resume-intelligence.svg" />
        </picture>
      </a>
    </td>
    <td width="50%">
      <a href="https://github.com/YousufS09/InventoryManagementSystem">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./assets/project-inventory.svg" />
          <source media="(prefers-color-scheme: light)" srcset="./assets/project-inventory-light.svg" />
          <img width="100%" alt="Inventory Management System: inventory operations by text or voice" src="./assets/project-inventory.svg" />
        </picture>
      </a>
    </td>
  </tr>
</table>

<br>

[![Code Review AI Agent](https://img.shields.io/badge/Code_Review_AI_Agent-View_repo-8250DF?style=flat-square&logo=github)](https://github.com/YousufS09/code-review-ai-agent)
[![Resume Intelligence Frontend](https://img.shields.io/badge/Resume_Intelligence-Frontend-0969DA?style=flat-square&logo=github)](https://github.com/YousufS09/resume_parser_fe)
[![Resume Intelligence Backend](https://img.shields.io/badge/Resume_Intelligence-Backend-0969DA?style=flat-square&logo=github)](https://github.com/YousufS09/Resume_parser_service)
[![Inventory Management System](https://img.shields.io/badge/Inventory_Management-View_repo-1A7F37?style=flat-square&logo=github)](https://github.com/YousufS09/InventoryManagementSystem)

</div>

<details>
<summary><strong>Under the hood: how the Code Review AI Agent works</strong></summary>
<br>

```mermaid
flowchart LR
    A[Pull request opened] -->|Signed webhook| B[Express API]
    B --> C{Verify signature<br/>validate + rate limit}
    C --> D[Review orchestrator]
    D --> E[GitHub service<br/>fetch changed files]
    E --> F[AI service<br/>Llama 3.3 70B via Groq]
    F --> G[Structured findings]
    G --> H[(PostgreSQL + Prisma)]
    G -->|Post or update review| A
```

</details>

<details>
<summary><strong>Under the hood: the Resume Intelligence parsing pipeline</strong></summary>
<br>

```mermaid
flowchart LR
    A[PDF / DOCX upload] --> B[Text extraction<br/>pdf-parse + Mammoth]
    B --> C{LLM extraction<br/>succeeds?}
    C -->|Yes| D[Llama 3.1 structured JSON]
    C -->|No| E[Rule-based parser]
    D --> F[(PostgreSQL)]
    E --> F
    F --> G[Recruiter dashboard]
```

</details>

## Journey

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/journey.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/journey-light.svg" />
  <img width="100%" alt="Journey: 2026 AI/ML Intern and Associate GenAI Engineer at Kaaylabs, next: building the next wave of AI products" src="./assets/journey.svg" />
</picture>

</div>

## Toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=python,js,react,html,css,nodejs,express,fastapi,mysql,postgres,prisma,git,github,vscode&perline=7" alt="Python, JavaScript, React, HTML, CSS, Node.js, Express, FastAPI, MySQL, PostgreSQL, Prisma, Git, GitHub, VS Code" />

<br><br>

![LLMs](https://img.shields.io/badge/LLMs-8250DF?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0969DA?style=for-the-badge&logo=semanticweb&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-1A7F37?style=for-the-badge&logo=probot&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-A371F7?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logoColor=white)
![Llama](https://img.shields.io/badge/Llama_3.x-0467DF?style=for-the-badge&logo=meta&logoColor=white)

</div>

## GitHub activity

<details>
<summary><strong>Latest activity</strong> <sub>(auto-updated daily)</sub></summary>
<br>

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

</details>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=YousufS09&show_icons=true&hide_border=true&theme=github_dark&rank_icon=github" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=YousufS09&show_icons=true&hide_border=true&theme=default&rank_icon=github" />
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YousufS09&show_icons=true&hide_border=true&theme=github_dark&rank_icon=github" alt="Mohamed Yousuf's GitHub statistics" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=YousufS09&layout=compact&hide_border=true&theme=github_dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=YousufS09&layout=compact&hide_border=true&theme=default" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YousufS09&layout=compact&hide_border=true&theme=github_dark" alt="Mohamed Yousuf's most used languages" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=YousufS09&theme=github-dark-blue&hide_border=true&background=0D1117&ring=8250DF&fire=58A6FF&currStreakLabel=58A6FF" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=YousufS09&theme=default&hide_border=true&ring=8250DF&fire=0969DA&currStreakLabel=0969DA" />
  <img src="https://streak-stats.demolab.com?user=YousufS09&theme=github-dark-blue&hide_border=true&background=0D1117&ring=8250DF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub contribution streak" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YousufS09/YousufS09/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YousufS09/YousufS09/output/github-contribution-grid-snake.svg" />
  <img alt="Animated contribution snake" src="https://raw.githubusercontent.com/YousufS09/YousufS09/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

<div align="center">

### Let's build something intelligent

Open to conversations about Generative AI, full-stack engineering and ambitious product ideas.

[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yousufmohameds)
[![Email me](https://img.shields.io/badge/Email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedyousufs.tech@gmail.com)
[![Explore repositories](https://img.shields.io/badge/Explore_repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YousufS09?tab=repositories)

![Footer](https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:8250DF,50:0969DA,100:0D1117&animation=fadeIn)

</div>
