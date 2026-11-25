<!--
  Profile README for https://github.com/BravesDevs
  Impact figures are the ones on Devang Parekh's resume.
  Stat cards and the contribution snake in ./profile are refreshed by
  .github/workflows/profile-cards.yml (push to main, daily, or manual run).
-->

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Devang%20Parekh&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=32&desc=AI%20Automation%20Engineer%20at%20Reklaim%20%C2%B7%20Toronto&descAlignY=55&descSize=18"/>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=720&height=40&lines=AI+Automation+Engineer+at+Reklaim;Agentic+systems%2C+RAG%2C+and+production+APIs;TypeScript+%C2%B7+Python+%C2%B7+Java+%C2%B7+SQL;Toronto+%C2%B7+open+to+collaboration" alt="AI Automation Engineer at Reklaim. Agentic systems, RAG, and production APIs. TypeScript, Python, Java, and SQL. Toronto." />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BravesDevs&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile views" />
  <a href="https://github.com/BravesDevs?tab=followers">
    <img src="https://img.shields.io/github/followers/BravesDevs?label=Followers&style=for-the-badge&color=236ad3&labelColor=0d1117&logo=github" alt="GitHub followers" />
  </a>
  <a href="https://github.com/BravesDevs?tab=repositories">
    <img src="https://img.shields.io/github/stars/BravesDevs?affiliations=OWNER&label=Stars&style=for-the-badge&color=e3b341&labelColor=0d1117&logo=github" alt="Stars on repositories I own" />
  </a>
</p>

## About

I build agentic systems and the backends they run on. The through-line is the same from Reklaim back through Playgrnd, FIYGE, and Maruti Techlabs: take a manual or slow workflow, put a reliable service under it, and measure the result.

```ts
const devang = {
  role: "AI Automation Engineer",
  company: "Reklaim",
  location: "Toronto, Ontario, Canada",
  focus: ["Agentic systems", "RAG and retrieval", "Production APIs"],
  stack: ["TypeScript", "Python", "Java", "PostgreSQL", "AWS"],
  now: "Agent workflows, observability, and a shared UI for agents",
};
```

- Shipping agent workflows at **Reklaim**, with Langfuse on the telemetry path and a shared component library for the agent UI.
- Public work is led by **[Agentable.io](https://github.com/BravesDevs/Agentable.io)**, a visual builder that turns a graph into a live REST endpoint.
- Day to day that is TypeScript and Next.js, Python and FastAPI, Java and Spring Boot, Postgres, and AWS.

## Experience

### Reklaim Inc. · AI Automation Engineer
Toronto, Ontario · Jun 2026 – Present

**−35%** monthly user cost (CA$4,800 → CA$3,100) · **62** shared UI components · human tone in agent replies

- Built custom skills and connected a Slack MCP so communications pull real human tone and context, eliminating 100% of robotic AI-sounding responses in that flow.
- Integrated Langfuse for telemetry and applied PStack and loop engineering, cutting monthly user cost by 35%, from CA$4,800 to CA$3,100.
- Implemented a Semantic UI package that gives agents reusable components, standardizing the interface across 62 components.

### Playgrnd · Full Stack AI Engineer
Toronto, Ontario · Nov 2025 – May 2026

**2** production agents · **98%** of the manual workflow automated · **+35%** counterparty profit · schema across **6** services

- Led an agentic workflow in Mastra, TypeScript, and Next.js. Two custom agents automated 98% of the manual tasks and increased counterparty profit by 35%.
- Designed the backend schema in Prisma and PostgreSQL across 6 services, and used prompt engineering and model tuning to improve classification and how results were stored.

### FIYGE Research Inc. · Software Engineer
Toronto, Ontario · Dec 2024 – Oct 2025

**500+** tables vectorized · **+60%** retrieval accuracy · **300+** APIs mapped · form time **−70%** · latency **78s → 22s** · database load **−30%**

- Built QueryGen with Pinecone, Hugging Face, and FastAPI. Vectorized 500+ tables and improved retrieval accuracy by 60%.
- Migrated a Chrome extension from V1 to V2, mapping 300+ APIs to automate webform workflows and cut completion time by 70%.
- Configured NGINX and cache bursting for the FIYGE service, bringing latency from 78s down to 22s.
- Integrated Spring Data JPA with MySQL and tuned high-traffic queries with connection pooling and batch writes, reducing database load by 30%.
- Built a Plaid banking service in Spring Boot, with scheduled sync via CRON.

### Maruti Techlabs · Software Engineer L2
Bengaluru, India · Aug 2021 – Apr 2023

**3** products, valued together at **US$800,000+** · downtime **−28%** · **25+** mailbox capabilities

- Engineered solutions for 3 products across hybrid chatbots, B2B, and healthcare, collectively valued at over US$800,000.
- Led the move to serverless ingest pipelines, which improved reliability and reduced downtime by 28%.
- Built a mailbox microservice with 25+ email capabilities for Google and Microsoft accounts, using the Nylas SDK.
- Set up CI/CD in GitHub Actions for container builds and deploys on AWS EC2, with credentials in AWS Secrets Manager.

## Selected work

These are the public repositories with a real product behind them.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BravesDevs/Agentable.io">Agentable.io</a></h3>
      Visual AI agent builder. A drag-and-drop canvas runs Claude and GPT-4o with token streaming over SSE, accepts text, files, and images, and exposes every flow as a REST endpoint.
      <br><br>
      <strong>Stack:</strong> Next.js 16, React Flow, Vercel AI SDK, Mastra, Neon Postgres, Drizzle, MCP, Langfuse
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BravesDevs/Finlysis">Finlysis</a></h3>
      Personal finance API. Plaid Link connects bank accounts, CSV import runs as a tracked batch, and the dashboard serves cash flow, burn rate, and merchant concentration.
      <br><br>
      <strong>Stack:</strong> NestJS, Prisma, MySQL, JWT, Plaid, Swagger
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BravesDevs/ConHacks2026">Infralens</a></h3>
      Built at ConHacks 2026. Watches Terraform changes, reads usage metrics, and opens a pull request with a right-sized configuration.
      <br><br>
      <strong>Stack:</strong> FastAPI, React, Postgres, Terraform, GitHub webhooks
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BravesDevs/Gujarati-Accent-Detection">Gujarati dialect detection</a></h3>
      Five-way classifier for Ahmedabadi, Charotari, Surati, Mahesani, and Kathiyavadi. Audio is transcribed first. The Keras model classifies the Gujarati transcript, behind a Django research UI.
      <br><br>
      <strong>Stack:</strong> Python, Django 5, Keras, SpeechRecognition
    </td>
  </tr>
</table>

Also on this account: [SonicAlpha](https://github.com/BravesDevs/SonicAlpha) (Apple Music chart ingestion with FastAPI and Selenium), [HighTunes](https://github.com/BravesDevs/hightunes) (NestJS music API), and [ds-a](https://github.com/BravesDevs/ds-a) (data structures and algorithms in Python).

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,java,bash,react,nextjs,nodejs&perline=8" alt="TypeScript, JavaScript, Python, Java, shell, React, Next.js, Node.js" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=nestjs,spring,flask,fastapi,graphql,prisma,postgres,mysql&perline=8" alt="NestJS, Spring, Flask, FastAPI, GraphQL, Prisma, PostgreSQL, MySQL" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,aws,docker,nginx,githubactions,linux,git,selenium&perline=8" alt="MongoDB, AWS, Docker, NGINX, GitHub Actions, Linux, Git, Selenium" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Mastra-6C47FF?style=for-the-badge" alt="Mastra" />
  <img src="https://img.shields.io/badge/RAG-0FA47F?style=for-the-badge" alt="RAG" />
  <img src="https://img.shields.io/badge/Pinecone-121212?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Langfuse-111111?style=for-the-badge" alt="Langfuse" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" />
</p>

## Activity

Cards are generated from this account and refreshed on a schedule. Followers and stars in the header are live.

<p align="center">
  <img height="195" src="./profile/stats.svg" alt="GitHub stats for BravesDevs" />
  <img height="195" src="./profile/top-langs.svg" alt="Most used languages on BravesDevs" />
</p>

<p align="center">
  <img height="195" src="https://streak-stats.demolab.com?user=BravesDevs&theme=tokyonight&hide_border=true" alt="GitHub contribution streak for BravesDevs" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=BravesDevs&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph for BravesDevs" />
</p>

<p align="center">
  <a href="https://leetcode.com/devangmp">
    <img src="https://leetcard.jacoblin.cool/devangmp?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats for devangmp" />
  </a>
</p>

### Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile/github-contribution-grid-snake.svg" />
    <img alt="Contribution graph for BravesDevs, drawn as a snake" src="./profile/github-contribution-grid-snake.svg" />
  </picture>
</p>

## Education

**Conestoga College** — Graduate Certificate, Web Development · Kitchener, Ontario · Sep 2023 – Dec 2024

**Dharmsinh Desai University** — Bachelor of Engineering, Computer Engineering · Nadiad, India · Aug 2018 – May 2021

## Connect

<p align="center">
  <a href="https://gigforge.io/p/devangparekh">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/bravesdevs">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/BravesDevs">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://leetcode.com/devangmp">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="mailto:devangparekh2014@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center">
  <strong>Open to work on agentic systems, retrieval pipelines, and backend platforms.</strong>
</p>

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>
