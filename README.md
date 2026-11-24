<div align="center">

<img src="assets/banner.svg" width="640" alt="Pankaj Pandey, QA Engineer: API and AI-assisted testing"/>

<br/>

<a href="https://www.linkedin.com/in/pankaj-pandey-46535b50"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:pankajpconnect@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

I test lending and banking platforms: API regression, accounting checks and production root-cause analysis. Outside work, I build tools that make **AI-written tests prove they catch real bugs**.

> A test suite is worth the bugs it catches, not the coverage it reports.

## Spotlight: [ai-test-case-generator](https://github.com/PankajPandey-codes/ai-test-case-generator)

Three Claude agents turn an API spec into a pytest suite. A reference app with **7 named, seeded bugs** (auth bypass, data leak, idempotency violation, …) then checks whether that suite actually catches them.

<p align="center"><img src="assets/pipeline-mobile.svg" width="420" alt="Pipeline: API spec → Generator → Critic (revise loop) → seeded-bug Harness → Judge → Gate"></p>

**7** seeded bugs &nbsp;·&nbsp; **~40-line** orchestrator, no framework &nbsp;·&nbsp; **≈ $0.11** per live run &nbsp;·&nbsp; **$0** CI on a fake LLM

**[Read the repo →](https://github.com/PankajPandey-codes/ai-test-case-generator)**

## More tools

**[flowforge](https://github.com/PankajPandey-codes/flowforge)**: turns recorded browser traffic into API test fixtures. Sensitive values are masked **before** anything reaches an LLM.<br/>
<sub>Python · mitmproxy · Flask</sub>

**[iris](https://github.com/PankajPandey-codes/iris)**: native macOS API console with collections, environments, request tests and a CSV batch runner.<br/>
<sub>Python · pywebview · JavaScript</sub>

**[pagewright](https://github.com/PankajPandey-codes/pagewright)**: desktop PDF editor. Edit existing text, add images and shapes, merge and split.<br/>
<sub>Java · Swing · PDFBox</sub>

## How I check AI output

I build with Claude Code and verify what it produces:

- **"The tests pass" isn't proof.** I seed known bugs and count how many the suite catches.
- **"The agent is done" isn't proof.** A Critic and a Judge agent review every Generator.
- **Checks must be repeatable.** CI runs against a fake LLM, so it is free and never flakes.
- **Data stays safe.** Sensitive values are masked before any prompt leaves the machine.

## Toolbox

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
<img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit 5"/>
<img src="https://img.shields.io/badge/JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white" alt="JMeter"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>
