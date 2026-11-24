<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:70a5fd,100:0d1117&height=200&section=header&text=Pankaj%20Pandey&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=QA%20Engineer%20%C2%B7%20AI-assisted%20Test%20Tooling&descAlignY=55&descSize=20" width="100%"/>

<a href="https://github.com/PankajPandey-codes">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=70A5FD&center=true&vCenter=true&repeat=true&width=800&height=45&lines=Seeded+bugs+over+coverage+percentages;AI-written+tests+that+prove+their+value;API+regression+for+lending+and+banking+platforms" alt="Typing SVG" />
</a>

<p>
  <img src="https://img.shields.io/badge/Focus-API_Testing_%26_AI_Agents-70a5fd?style=for-the-badge" alt="focus"/>
  <img src="https://img.shields.io/badge/Stack-Python_%C2%B7_Java-70a5fd?style=for-the-badge" alt="stack"/>
  <img src="https://komarev.com/ghpvc/?username=PankajPandey-codes&style=for-the-badge&color=70a5fd" alt="views"/>
</p>

<p>
  <a href="https://www.linkedin.com/in/pankaj-pandey-46535b50"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:pankajpconnect@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

</div>

---

## 👨‍💻 About Me

**QA engineer building AI-assisted test tooling.** I work on lending and banking platforms: API regression, accounting checks and production root-cause analysis. In my own time I build tools that make AI-written tests prove their value.

> I'd rather show a seeded bug being caught than a coverage percentage.

🔭 **Building:** agent pipelines that generate and then *audit* API test suites

🌱 **Learning:** LLM agent design, evals, cost-controlled agent runs

💬 **Ask me about:** API regression, accounting/ledger testing, pytest, JUnit, RCA

---

## ⭐ Featured: ai-test-case-generator

Three Claude agents write a pytest suite from an API spec. A reference app with **7 named, seeded bugs** (auth bypass, data leak, idempotency violation, …) then checks whether that suite actually catches them.

<p align="center"><img src="assets/pipeline.svg" width="100%" alt="Pipeline: API spec → Generator → Critic (revise loop) → seeded-bug Harness → Judge → Gate" /></p>

No agent framework: the orchestration is a single ~40-line function with typed contracts at every step. CI runs the full suite against a fake LLM client, so it costs nothing and never flakes. A live run costs about $0.11. → [Read the repo](https://github.com/PankajPandey-codes/ai-test-case-generator)

<div align="center">
  <a href="https://github.com/PankajPandey-codes/ai-test-case-generator"><img src="https://github-readme-stats.vercel.app/api/pin/?username=PankajPandey-codes&repo=ai-test-case-generator&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&icon_color=70a5fd&text_color=ffffff"/></a>
</div>

---

## 🛠️ More Tools

<table>
<tr>
<td width="50%" valign="top">

**[flowforge](https://github.com/PankajPandey-codes/flowforge)**<br>
Records real browser traffic and turns it into API test fixtures. Sensitive values are masked before anything reaches an LLM.<br>
<sub>Python · mitmproxy · Flask</sub>

</td>
<td width="50%" valign="top">

**[java-regression-runner](https://github.com/PankajPandey-codes/java-regression-runner)**<br>
CSV/JSON-manifest API regression runner with step chaining, SQL steps, HTML reports and unattended overnight runs.<br>
<sub>Java 17 · JUnit · SQL</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[iris](https://github.com/PankajPandey-codes/iris)**<br>
Native macOS API console with collections, environments, request tests and a CSV batch runner.<br>
<sub>Python · pywebview · JavaScript</sub>

</td>
<td width="50%" valign="top">

**[pagewright](https://github.com/PankajPandey-codes/pagewright)**<br>
Desktop PDF editor: edit existing text, add text, images and shapes, merge and split.<br>
<sub>Java · Swing · PDFBox</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[jobscout](https://github.com/PankajPandey-codes/jobscout)**<br>
Upload a CV, get ranked roles, skill gaps and a calibrated salary range, with every agent step visible. Real postings from open company boards.<br>
<sub>Python · LLM agent</sub>

</td>
<td width="50%" valign="top">

**[riggr](https://github.com/PankajPandey-codes/riggr)**<br>
Multi-harness agent toolkit: skills, agents, hooks and rules for Claude Code, Codex, Cursor and more. Adapted from the MIT-licensed [affaan-m/ECC](https://github.com/affaan-m/ECC), attribution retained.<br>
<sub>Agent tooling</sub>

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">
<table>
<tr>
<td valign="top" width="33%">
<h3 align="center">🧪 Testing</h3>
<div align="center">
<img src="https://img.shields.io/badge/PyTest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest"/>
<img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="junit"/>
<img src="https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white" alt="jmeter"/>
<img src="https://img.shields.io/badge/mitmproxy-5C2D91?style=for-the-badge" alt="mitmproxy"/>
</div>
</td>
<td valign="top" width="33%">
<h3 align="center">💻 Development</h3>
<div align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
</div>
</td>
<td valign="top" width="33%">
<h3 align="center">🤖 AI &amp; Tools</h3>
<div align="center">
<img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API"/>
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</div>
</td>
</tr>
</table>
</div>

---

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=PankajPandey-codes&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&icon_color=70a5fd&text_color=ffffff"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PankajPandey-codes&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&text_color=ffffff&langs_count=6"/>
</div>

---

## 🧭 How I Build

- **A test suite is only as good as the bugs it catches.** I measure that with seeded bugs, not coverage.
- **Honest scope.** Each README says what is out of scope and where the tool stops.
- **Local-first.** No hosted service needed; the LLM-backed tools use your own API key.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:70a5fd,100:0d1117&height=120&section=footer" width="100%"/>

</div>
