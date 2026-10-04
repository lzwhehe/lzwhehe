<div align="center">

<img src="assets/banner.svg" width="100%" alt="Liu Zhuowen — AI / Agent Security Researcher">

<a href="https://github.com/lzwhehe"><img src="https://img.shields.io/badge/中文-161b22?style=for-the-badge" alt="中文"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.en.md"><img src="https://img.shields.io/badge/English-22d3ee?style=for-the-badge" alt="English"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.ja.md"><img src="https://img.shields.io/badge/日本語-161b22?style=for-the-badge" alt="日本語"></a>

<a href="mailto:ryutakubunwork@gmail.com"><img src="https://img.shields.io/badge/Email-ryutakubunwork%40gmail.com-0b0f17?style=for-the-badge&labelColor=161b22&logo=gmail&logoColor=f5b041" alt="Email"></a> <a href="https://arxiv.org/abs/2609.33446"><img src="https://img.shields.io/badge/arXiv-2609.33446-0b0f17?style=for-the-badge&labelColor=161b22&logo=arxiv&logoColor=f87171" alt="arXiv"></a> <a href="https://doi.org/10.5281/zenodo.23133690"><img src="https://img.shields.io/badge/DOI-zenodo.23133690-0b0f17?style=for-the-badge&labelColor=161b22&logo=zenodo&logoColor=22d3ee" alt="DOI"></a>

</div>

<br>

Hi, I'm Liu Zhuowen, a second-year M.S. student in the **Cybersecurity Lab, Graduate School of Advanced Science and Technology, JAIST**.

My research focuses on **agent security in security operations (SOC)**, with the goal of putting LLM agents to work in real-world security operations safely and reliably. Alongside this, I work on **safeguarding China’s intangible cultural heritage**, using today’s most capable AI to help traditional culture be preserved and passed on digitally.

> [!TIP]
> Looking for **security / AI security roles (class of 2027)**: security research · security operations · AI security engineering.

<br>

<div align="center">
<img src="assets/terminal.svg" width="100%" alt="HESP triage demo: the model reads the logs, a controller decides">
</div>

## 🔬 Research

<img src="assets/card-now.svg" width="100%" alt="Now: premature verdicts under forged evidence">

<a href="https://github.com/lzwhehe/HESP"><img src="assets/card-hesp.svg" width="100%" alt="HESP"></a>

<a href="https://github.com/lzwhehe/benign-instruction-bench"><img src="assets/card-bench.svg" width="100%" alt="Passing the Test You Trained On"></a>

<a href="https://github.com/lzwhehe/kushulan-papercut-blora"><img src="assets/card-kushulan.svg" width="100%" alt="Safeguarding Intangible Heritage"></a>

<details>
<summary><b>One line per project</b></summary>

- **In progress · Premature verdicts under forged evidence**: ~10k episodes across open models from 0.5B to 72B (Qwen2.5, Qwen3, Llama-3.1, Meta-SecAlign). Models large enough to conclude judge 30–36 of 36 attacks benign under forged logs; Qwen2.5-72B accepts a story after checking 1.1 sources on average. Now pre-registering corroboration-aware training that uses no attack samples.
- **[HESP](https://github.com/lzwhehe/HESP)** (first author): the model reads the logs, a controller decides. After a log-format change, “7B reads, controller decides” resolves all 48 cases; a *reader-trust* rule brings missed attacks to 0 under every attack tested.
- **[Passing the Test You Trained On](https://github.com/lzwhehe/benign-instruction-bench)** (paper draft): rankings of 15 prompt-injection detectors barely transfer across benchmarks (Kendall τ 0.01–0.31); scores mostly reflect how close a benchmark is to a detector's training data.
- **[Ku Shulan paste-up papercut generation](https://github.com/lzwhehe/kushulan-papercut-blora)** (co-first author, under review at *npj Heritage Science*): recover the paper palette and cut lines from her works, then fine-tune Qwen-Image-Edit; line recall 0.97.

</details>

## 🧰 Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,git,latex,js,c&theme=dark" alt="Python · PyTorch · Git · LaTeX · JavaScript · C">
</p>

| Area | What I use |
| :-- | :-- |
| **Agent&nbsp;security** | indirect prompt injection · evidence forgery · adaptive attacks · reader trust / cross-source corroboration · OWASP LLM Top 10 |
| **Evaluation** | pre-registered experiments · write-ahead journals & independent verifiers · AgentDojo · τ-bench · BIPIA · SigmaHQ / ATT&CK |
| **LLM** | vLLM · Ollama · local Qwen2.5 / Qwen3 / Llama-3.1 · MCP · LoRA fine-tuning (Qwen-Image-Edit, SDXL) |
| **Web&nbsp;security** | OWASP Top 10 · Burp Suite · SQLMap · Nmap · Xray |

<div align="center">
<br>
<sub>Japan Advanced Institute of Science and Technology (JAIST) · Ishikawa, Japan · <i>let the model read, not decide.</i></sub>
</div>
