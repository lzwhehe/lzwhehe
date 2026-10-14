<div align="center">

<img src="assets/banner.svg?v=2" width="100%" alt="Liu Zhuowen — AI / Agent Security Researcher">

<a href="https://github.com/lzwhehe"><img src="https://img.shields.io/badge/中文-22d3ee?style=for-the-badge" alt="中文"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.en.md"><img src="https://img.shields.io/badge/English-161b22?style=for-the-badge" alt="English"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.ja.md"><img src="https://img.shields.io/badge/日本語-161b22?style=for-the-badge" alt="日本語"></a>

<a href="mailto:ryutakubunwork@gmail.com"><img src="https://img.shields.io/badge/Email-ryutakubunwork%40gmail.com-0b0f17?style=for-the-badge&labelColor=161b22&logo=gmail&logoColor=f5b041" alt="Email"></a>

</div>

<br>

你好，我是刘卓文，目前在**北陆先端科学技术大学院大学（JAIST）先端科学技术专攻 · 网络安全实验室**攻读硕士二年级。

我的研究聚焦**安全运营场景下的 Agent 安全**，致力于让 LLM 智能体安全、可靠地落地于实际的安全运营工作。同时，我也投身于**中国非物质文化遗产保护**，专注于用前沿 AI 技术助力传统文化的数字化保存与传承。


## 🔬 Research

<img src="assets/card-now.svg" width="100%" alt="Forged logs vs. LLM triage agents">

<a href="https://github.com/lzwhehe/HESP"><img src="assets/card-hesp.svg?v=2" width="100%" alt="HESP"></a>

<a href="https://github.com/lzwhehe/benign-instruction-bench"><img src="assets/card-bench.svg" width="100%" alt="Passing the Test You Trained On"></a>

<a href="https://github.com/lzwhehe/kushulan-papercut-blora"><img src="assets/card-kushulan.svg" width="100%" alt="Safeguarding Intangible Heritage"></a>

<details>
<summary><b>每个项目一句话</b></summary>

- **预印本 · 训练能否让小模型研判 Agent 识破伪造日志**（第一作者，DOI 10.5281/zenodo.23311714）：对 22 个模型配置（0.5B–72B）做 1.1 万回合伪造日志红队评测，4B–72B 中能结案的模型对 36 个攻击放行 30–36 个，而它们多半已经查到了与之矛盾的真实记录。LoRA SFT + GRPO 微调对齐后，留出告警漏报由 58/144 降到 7/144；正在补充实验。
- **[HESP](https://github.com/lzwhehe/HESP)**（第一作者，arXiv:2609.33446）：控制器接管“查什么”与“何时停”，模型只负责提议；计数似然表使 Qwen2.5-7B 完成率 0.125 → 1.000，控制器结案使 Llama-3.1-8B 0 → 0.917（4 项预注册研究、7,272 个审计回合）。
- **[Passing the Test You Trained On](https://github.com/lzwhehe/benign-instruction-bench)**（独立作者，arXiv:2610.03448）：重放 AgentDojo / τ-bench 的真实工具输出，重评 15 个提示词注入检测器与 2 个 LLM 裁判；BIPIA 榜首在 1% 误报率下只检出约 2% 的 AgentDojo 注入，并审计出其训练集含 1,116 条 BIPIA 输入。
- **[库淑兰彩贴剪纸生成](https://github.com/lzwhehe/kushulan-papercut-blora)**（共同一作，npj Heritage Science 审稿中）：从作品自动恢复纸色谱与剪切线，微调 Qwen-Image-Edit，线条召回 0.97。

</details>

## 🧰 Skills

<p align="center">
  <img src="https://img.shields.io/badge/Web_安全-f87171?style=for-the-badge" alt="Web 安全">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Burp_Suite-161b22?style=for-the-badge&logo=burpsuite&logoColor=FF6633" alt="Burp Suite"> <img src="https://img.shields.io/badge/SQLMap-161b22?style=for-the-badge" alt="SQLMap"> <img src="https://img.shields.io/badge/Nmap-161b22?style=for-the-badge" alt="Nmap"> <img src="https://img.shields.io/badge/Xray-161b22?style=for-the-badge" alt="Xray"> <img src="https://img.shields.io/badge/OWASP_Top_10-161b22?style=for-the-badge&logo=owasp&logoColor=ffffff" alt="OWASP Top 10">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Agent_工具-22d3ee?style=for-the-badge" alt="Agent 工具">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Claude_Code-161b22?style=for-the-badge&logo=claude&logoColor=D97757" alt="Claude Code"> <img src="https://img.shields.io/badge/Codex-161b22?style=for-the-badge" alt="Codex"> <img src="https://img.shields.io/badge/OpenCode-161b22?style=for-the-badge&logo=opencode&logoColor=ffffff" alt="OpenCode"> <img src="https://img.shields.io/badge/WorkBuddy-161b22?style=for-the-badge" alt="WorkBuddy"> <img src="https://img.shields.io/badge/Kimi_Code-161b22?style=for-the-badge&logo=kimi&logoColor=ffffff" alt="Kimi Code">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/开发能力-a78bfa?style=for-the-badge" alt="开发能力">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Vue-161b22?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue"> <img src="https://img.shields.io/badge/Node.js-161b22?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js"> <img src="https://img.shields.io/badge/vLLM-161b22?style=for-the-badge" alt="vLLM"> <img src="https://img.shields.io/badge/Ollama-161b22?style=for-the-badge&logo=ollama&logoColor=ffffff" alt="Ollama"> <img src="https://img.shields.io/badge/LoRA-161b22?style=for-the-badge" alt="LoRA"> <img src="https://img.shields.io/badge/Hyperledger_Fabric-161b22?style=for-the-badge" alt="Hyperledger Fabric">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/编程语言-f5b041?style=for-the-badge" alt="编程语言">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Python-161b22?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python"> <img src="https://img.shields.io/badge/JavaScript-161b22?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/TypeScript-161b22?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript"> <img src="https://img.shields.io/badge/C-161b22?style=for-the-badge&logo=c&logoColor=A8B9CC" alt="C">
</p>

