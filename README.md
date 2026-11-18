# Pankaj Pandey

**QA engineer building AI-assisted test tooling.** I work on lending and banking platforms: API regression, accounting checks and production root-cause analysis. In my own time I build tools that make AI-written tests prove their value.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pankaj--pandey-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pankaj-pandey-46535b50)
[![Email](https://img.shields.io/badge/Email-pankajpconnect%40gmail.com-444444?style=flat&logo=gmail&logoColor=white)](mailto:pankajpconnect@gmail.com)

> I'd rather show a seeded bug being caught than a coverage percentage.

---

### Featured: ai-test-case-generator

Three Claude agents write a pytest suite from an API spec. A reference app with **7 named, seeded bugs** (auth bypass, data leak, idempotency violation, …) then checks whether that suite actually catches them.

```mermaid
flowchart LR
    S[API spec] --> G[Generator agent]
    G --> C{Critic agent}
    C -- revise, max 1 retry --> G
    C -- accept --> H[Harness: run suite against 7 seeded bugs]
    H --> J[Judge agent: rubric score]
    J --> Q{Gate}
    Q -->|baseline passes, at least 70% caught, score at least 3.5| P[Pass]
    Q -->|otherwise| F[Fail]
```

No agent framework: the orchestration is a single ~40-line function with typed contracts at every step. CI runs the full suite against a fake LLM client, so it costs nothing and never flakes. A live run costs about $0.11. → [Read the repo](https://github.com/PankajPandey-codes/ai-test-case-generator)

---

### More tools

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
</table>

<sub>Also: [riggr](https://github.com/PankajPandey-codes/riggr), an agent-harness toolkit adapted from the MIT-licensed [affaan-m/ECC](https://github.com/affaan-m/ECC), with attribution retained.</sub>

---

### How I build

- **A test suite is only as good as the bugs it catches.** I measure that with seeded bugs, not coverage.
- **Honest scope.** Each README says what is out of scope and where the tool stops.
- **Local-first.** No hosted service needed; the LLM-backed tools use your own API key.

### Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=python,java,js,fastapi,flask,mysql,githubactions&theme=light" alt="Python, Java, JavaScript, FastAPI, Flask, MySQL, GitHub Actions" />
</p>

pytest · JUnit · mitmproxy · JMeter · Claude API · Claude Code
