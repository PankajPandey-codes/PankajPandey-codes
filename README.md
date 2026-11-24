<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f5fd0,100:7b2ff7&height=150&animation=fadeIn&section=header&text=Pankaj%20Pandey&fontSize=44&fontColor=ffffff&fontAlignY=40&desc=QA%20engineer%20%C2%B7%20AI-assisted%20test%20tooling&descAlignY=62&descSize=18" width="100%" alt="Pankaj Pandey, QA engineer, AI-assisted test tooling"/>

**I build tools that check whether AI-written tests are actually any good.**

<a href="https://www.linkedin.com/in/pankaj-pandey-46535b50"><img src="https://img.shields.io/badge/LinkedIn-pankaj--pandey-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:pankajpconnect@gmail.com"><img src="https://img.shields.io/badge/Email-get%20in%20touch-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

<br/>

I test lending and banking platforms for a living: API regression, accounting checks, production root-cause analysis. These repos are what I build on the side.

> I'd rather show a seeded bug being caught than quote a coverage percentage.

## Featured: ai-test-case-generator

Three Claude agents write a pytest suite from an API spec. A reference app with **7 named, seeded bugs** (auth bypass, data leak, idempotency violation, …) then checks whether that suite actually catches them.

<p align="center"><img src="assets/pipeline.svg" width="100%" alt="Pipeline: API spec → Generator → Critic (revise loop) → seeded-bug Harness → Judge → Gate" /></p>

| | |
|---|---|
| **No framework** | The orchestration is one ~40-line function with typed contracts at every step |
| **Free CI** | The full suite runs against a fake LLM client: no cost, no flakes |
| **Cheap live run** | About **$0.11** per real run |

**[Read the repo →](https://github.com/PankajPandey-codes/ai-test-case-generator)**

## More work

<table>
<tr>
<td width="33%" valign="top">

### [flowforge](https://github.com/PankajPandey-codes/flowforge)
Turns recorded browser traffic into API test fixtures, masking sensitive values before anything reaches an LLM.

<sub>Python · mitmproxy · Flask</sub>

</td>
<td width="33%" valign="top">

### [java-regression-runner](https://github.com/PankajPandey-codes/java-regression-runner)
CSV/JSON-driven API regression runner: step chaining, SQL steps, HTML reports, unattended overnight runs.

<sub>Java 17 · JUnit · SQL</sub>

</td>
<td width="33%" valign="top">

### [jobscout](https://github.com/PankajPandey-codes/jobscout)
Upload a CV, get ranked roles, skill gaps and a salary range, with every agent step visible.

<sub>Python · LLM agent</sub>

</td>
</tr>
<tr>
<td valign="top">

### [iris](https://github.com/PankajPandey-codes/iris)
Native macOS API console: collections, environments, request tests, CSV batch runner.

<sub>Python · pywebview · JS</sub>

</td>
<td valign="top">

### [pagewright](https://github.com/PankajPandey-codes/pagewright)
Desktop PDF editor: edit text, add images and shapes, merge and split.

<sub>Java · Swing · PDFBox</sub>

</td>
<td valign="top">

### [riggr](https://github.com/PankajPandey-codes/riggr)
Agent-harness toolkit for Claude Code, Codex, Cursor and more. Adapted from MIT-licensed [affaan-m/ECC](https://github.com/affaan-m/ECC).

<sub>Agent tooling</sub>

</td>
</tr>
</table>

## How I work

- **Measure what a test suite catches**, not how many lines it covers.
- **Say where the tool stops.** Every README lists what is out of scope.
- **Local-first.** No hosted service; LLM-backed tools use your own API key.

<p align="center"><b>Python</b> · <b>Java</b> · <b>JavaScript</b> · FastAPI · Flask · MySQL · GitHub Actions<br/><sub>pytest · JUnit · mitmproxy · JMeter · Claude API · Claude Code</sub></p>
