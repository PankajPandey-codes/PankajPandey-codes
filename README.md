## Pankaj Pandey

QA engineer on lending and banking platforms, working on API regression, accounting checks and production root-cause analysis.

Outside work I build tools that make AI-written tests prove their value. I'd rather show a seeded bug being caught than a coverage percentage.

### Selected work

- **[ai-test-case-generator](https://github.com/PankajPandey-codes/ai-test-case-generator)**: Generator → Critic → Judge agents turn an API spec into a pytest suite. A reference app ships with 7 named, seeded bugs (auth bypass, data leak, idempotency violation, …). The pipeline passes only if the clean baseline passes, the suite catches at least 70% of the seeded bugs and the judge scores it at least 3.5.
- **[flowforge](https://github.com/PankajPandey-codes/flowforge)**: records real browser traffic and turns it into API test fixtures, masking sensitive values before anything is sent to an LLM.
- **[java-regression-runner](https://github.com/PankajPandey-codes/java-regression-runner)**: CSV/JSON-manifest API regression runner for Java 17, with declarative assertions, step chaining, SQL steps, HTML reports and unattended overnight runs.
- **[iris](https://github.com/PankajPandey-codes/iris)**: native macOS API console with collections, environments, request tests and a CSV batch runner.

Other: [pagewright](https://github.com/PankajPandey-codes/pagewright) (desktop PDF editor) · [riggr](https://github.com/PankajPandey-codes/riggr) (agent-harness toolkit adapted from the MIT-licensed [affaan-m/ECC](https://github.com/affaan-m/ECC), with attribution retained)

### How I build

- A test suite is only as good as the bugs it catches.
- READMEs say what is out of scope and where the tool stops.
- Local-first: no hosted service. The LLM-backed tools use your own API key.

### Contact

[LinkedIn](https://www.linkedin.com/in/pankaj-pandey-46535b50) · [pankajpconnect@gmail.com](mailto:pankajpconnect@gmail.com). Always glad to compare notes on AI-assisted testing.
