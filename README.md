<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Cascadia+Code&weight=700&size=18&duration=1&pause=100000&color=D58BB7&center=true&vCenter=true&width=720&lines=Hi,+I'm+Hyerin.+I+make+AI+you+can+measure+and+trust." alt="Hi, I'm Hyerin." />
  <br/>
  <img src="https://readme-typing-svg.herokuapp.com?font=Cascadia+Code&size=15&duration=1&pause=100000&color=8AA7D6&center=true&vCenter=true&width=760&lines=AI+Evaluation+%7C+LLM/RAG+%7C+Agent+Harness+%7C+Statistical+Rigor" alt="Current focus" />
  
  <p>
    <code>Gachon University · AI</code>
    <code>Seoul / Remote</code>
    <code>Open to AI/ML internship &amp; new-grad roles</code>
  </p>
</div>

I focus on **evaluating** AI systems — whether a model or agent is *actually* better, by how much, and at what cost — not just getting a demo to answer.

- Most AI demos stop at "it answered." I care about the next questions: did it find the right evidence, did it stay grounded, was the improvement real or just noise, and what did it cost?
- The through-line across my projects is a shared evaluation methodology — the same significance tests power both my agent harness and my RAG lab.
- My workflow: build a small version, test it, write the failure down honestly, then improve it.
- Cute on the outside, honest on the inside.

### Projects

**[rag-trust-lab](https://github.com/chohyerinn/rag-trust-lab)** — RAG 평가 랩: 근거성, 프롬프트 인젝션, 오염문서 노출까지. recall@3 56%→100%, 오염 노출 55%→0% (p=0.001).
**[mini-agent-harness](https://github.com/chohyerinn/mini-agent-harness)** — 코딩 에이전트 평가 하네스: pass@k, bootstrap/McNemar 유의성, 변조 탐지, 비용.
**[certainty-inference](https://github.com/chohyerinn/certainty-inference)** — 확실성 추론 (NIKL·말평): 공식 리더보드 **1위**.
**[muton](https://github.com/chohyerinn/muton)** — 농인 대화보조 졸업작품 (Android 담당): LoRA 적용 후 사람평가 10.7→16.6/20.

### How I evaluate

- **Repeated runs over single runs** — LLMs are non-deterministic, so I report pass@k, variance, and failure types instead of one lucky pass.
- **Significance, not vibes** — paired bootstrap 95% CI + McNemar test to separate a real improvement from noise.
- **Cost as a first-class metric** — marginal tokens per additional solved task, because "better" is rarely free.
- **Failure & trust** — grounding, prompt-injection following, poisoned-document exposure, and tamper detection.

### Links

<p>
  <a href="mailto:chohyerinn03@gmail.com">
    <img src="https://img.shields.io/badge/Email-chohyerinn03%40gmail.com-F4A7B9?style=flat-square&logo=gmail&logoColor=white" alt="email" />
  </a>
  <a href="https://github.com/chohyerinn">
    <img src="https://img.shields.io/badge/GitHub-chohyerinn-9BB7D4?style=flat-square&logo=github&logoColor=white" alt="github" />
  </a>
  <a href="https://github.com/chohyerinn?tab=repositories">
    <img src="https://img.shields.io/badge/Repos-my%20project-A7C7A1?style=flat-square&logo=githubsponsors&logoColor=white" alt="repositories" />
  </a>
</p>

### Open Source

**[punkpeye/awesome-mcp-servers#8399](https://github.com/punkpeye/awesome-mcp-servers/pull/8399)**  
Added `filter-mcp-server` to the Data Science Tools category after passing build, MCP introspection, license, and quality checks.
