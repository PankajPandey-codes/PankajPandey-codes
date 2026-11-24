<div align="center">

<img src="assets/banner.svg" width="100%" alt="Pankaj Pandey: I make AI-written tests prove they work"/>
<br/><br/>

<a href="https://www.linkedin.com/in/pankaj-pandey-46535b50"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:pankajpconnect@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Based_in-India-5b3df5?style=for-the-badge" alt="Based in India"/>

</div>

### 👋 In 30 seconds

- 🏦 **By day:** QA engineer on lending and banking platforms: API regression, ledger and accounting checks, production root-cause analysis.
- 🤖 **By night:** I build agent pipelines that **write** API tests and then **audit** them against seeded bugs.
- 🎯 **My rule:** a test suite is worth the bugs it catches, not the coverage it reports.

---

## ⭐ Featured · [ai-test-case-generator](https://github.com/PankajPandey-codes/ai-test-case-generator)

Three Claude agents turn an API spec into a pytest suite. A reference app with **7 named, seeded bugs** (auth bypass, data leak, idempotency violation, …) then checks whether that suite actually catches them.

<p align="center"><img src="assets/pipeline.svg" width="100%" alt="Pipeline: API spec → Generator → Critic (revise loop) → seeded-bug Harness → Judge → Gate" /></p>

<div align="center">

| 🐞 Seeded bugs | 🧩 Orchestration | 💸 Live run | ✅ CI |
|:---:|:---:|:---:|:---:|
| **7** named | **~40 lines**, no framework | **≈ $0.11** | fake LLM, **$0**, no flakes |

</div>

---

## 🛠️ Tools I've built

<table>
<tr>
<td colspan="2" valign="top">

### 🔎 [jobscout](https://github.com/PankajPandey-codes/jobscout): an AI job-match agent
Upload a CV, get ranked roles, skill gaps and a calibrated salary range, with every agent step visible.

<a href="https://github.com/PankajPandey-codes/jobscout"><img src="assets/jobscout-hero.png" width="100%" alt="jobscout: turn your CV into a ranked shortlist of roles"/></a>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LLM agent](https://img.shields.io/badge/LLM_agent-D97757?style=flat-square&logo=anthropic&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌊 [flowforge](https://github.com/PankajPandey-codes/flowforge)
Records real browser traffic and turns it into API test fixtures. Sensitive values are masked **before** anything reaches an LLM.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![mitmproxy](https://img.shields.io/badge/mitmproxy-5C2D91?style=flat-square) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

</td>
<td width="50%" valign="top">

### ☕ [java-regression-runner](https://github.com/PankajPandey-codes/java-regression-runner)
API regression from CSV/JSON manifests: step chaining, SQL steps, HTML reports, unattended overnight runs.

![Java 17](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 [iris](https://github.com/PankajPandey-codes/iris)
Native macOS API console: collections, environments, request tests and a CSV batch runner.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![macOS](https://img.shields.io/badge/macOS-999999?style=flat-square&logo=apple&logoColor=white)

</td>
<td width="50%" valign="top">

### 📄 [pagewright](https://github.com/PankajPandey-codes/pagewright)
Desktop PDF editor: edit existing text, add images and shapes, merge and split.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Swing](https://img.shields.io/badge/Swing-5382A1?style=flat-square) ![PDFBox](https://img.shields.io/badge/PDFBox-D22128?style=flat-square&logo=apache&logoColor=white)

</td>
</tr>
</table>

---

## 🤖 How I use AI, and how I check it

I build with Claude Code, and I don't take its output on trust:

| I don't trust… | So I… |
|---|---|
| "The tests pass" | Seed known bugs and measure how many the suite catches |
| "The agent is done" | Put a Critic and a Judge agent behind every Generator |
| "It works on my key" | Run CI against a fake LLM so every check is free and repeatable |
| "It handles data safely" | Mask sensitive values before any prompt leaves the machine |

---

## 🧰 Toolbox

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white)
<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

<div align="center">

**Working on AI-assisted testing too? I'd like to compare notes.**

<a href="https://www.linkedin.com/in/pankaj-pandey-46535b50"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:pankajpconnect@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>


</div>
