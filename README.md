<div align="center">

# 刘卓文 · Liu Zhuowen

**AI / Agent 安全 · 网络安全 · LLM 安全评测**

JAIST 网络安全实验室 · 计算机科学硕士（2027.03 毕业）

[![Email](https://img.shields.io/badge/Email-ryutakubun%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ryutakubun@gmail.com)
[![arXiv](https://img.shields.io/badge/arXiv-2609.33446-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2609.33446)
![Languages](https://img.shields.io/badge/中文%20·%20日本語%20N1%20·%20English-555?style=flat-square)

</div>

我研究 **LLM Agent 在安全场景里能不能被信任**：小模型能不能可靠地做安全告警分诊，提示词注入从哪里进来、怎么挡住，以及检测器的跑分能不能代表它在真实 Agent 里的表现。本科读信息安全，有 Web 渗透和攻防竞赛的基础；硕士在北陆先端科学技术大学院大学（JAIST）做 Agent 安全研究。

我的研究习惯是：**实验先登记再运行，每个数字都能从公开的日志和脚本重新算出来。**

> 🔎 正在寻找 **2027 届网络安全 / AI 安全**相关岗位（安全研究、安全运营、AI 安全工程）。

---

## 研究项目

### 🛡️ [HESP](https://github.com/lzwhehe/HESP)：让 7B 模型胜任告警分诊

*Making Small Local LLMs Usable for Alert Triage — The Model Reads the Logs, a Controller Decides* · 第一作者 · [arXiv:2609.33446](https://arxiv.org/abs/2609.33446)

数据不能出域的组织只能用本地小模型分诊告警，而小模型单独做不到。HESP 把分诊拆成两件事：**模型负责读日志，控制器负责做决定**（贝叶斯假设账本 + 按单位成本信息增益选探针 + 证据守卫）。

- **两半都不能单独工作**：日志格式一变，规则解析器 364 条观测全部读错；Qwen2.5-7B 自己决策时，面对原始日志 48 例一个都解决不了；“7B 模型读、控制器判”则 48 例全部解决。
- **读取本身就是攻击面**：攻击者在每条日志里写进同一个“良性”故事，7B 模型就把 36 个攻击全部判为良性。HESP 不让模型读出的证据支持良性结论，挡住了所有测试过的攻击。
- **可复现**：5 个开源模型（7B–72B）、三个模拟分诊环境、全部实验预注册，23,582 个 LLM 回合逐一审计；代码、预测表和回合日志全部公开。

### 🧪 [benign-instruction-bench](https://github.com/lzwhehe/benign-instruction-bench)：*Passing the Test You Trained On*

重新评估**提示词注入检测器**：在 Agent 真正读取的工具输出上，检测器的跑分还靠得住吗？

- 评测 15 个检测器（含 Meta Prompt Guard 2）和 2 个任务感知的 LLM 裁判，覆盖 AgentDojo、τ-bench 和 BIPIA。
- **排名在基准之间几乎不迁移**（Kendall τ 仅 0.01–0.31）：BIPIA 第一名在 AgentDojo 上排第 13；良性工具输出上的误报率从 0% 到 90% 以上不等。
- 结论：基准分数主要反映的是**基准与检测器训练数据有多接近**，而不是检测能力本身。（论文草稿）

### 🎨 [库淑兰彩贴剪纸设计生成](https://github.com/lzwhehe/kushulan-papercut-blora)：非遗 × 生成模型

*Safeguarding intangible heritage in folk papercut* · 共同第一作者 · 已投稿 *npj Heritage Science*（审稿中）

国家级非遗“旬邑彩贴剪纸”里，每条颜色边界都是剪刀走过的线。据此从作品中自动恢复纸色谱和剪切线，用“剪切线 → 作品”数据微调 Qwen-Image-Edit，让任意线稿都能生成库淑兰风格的设计。

- 34 张测试线稿（含 12 个她从未剪过的新题材）：线条召回 **0.97**、CLIP 风格 **0.848**，均优于 B-LoRA、InstantStyle 等四个主流框架。
- 剪切线训练让每幅设计的用色数从 9.8 降到 7.9，更接近原作的 6.1。

---

## 技术栈

**安全**：Web 渗透（OWASP Top 10、Burp Suite、SQLMap、Nmap）· 告警研判 · Sigma / ATT&CK · OWASP LLM Top 10 · 提示词注入攻防

**LLM / Agent**：vLLM · Ollama · Qwen2.5 / Llama-3.1 本地部署 · MCP · Agent 评测设计

**机器学习**：PyTorch · LoRA 微调（Qwen-Image-Edit、SDXL）· 统计检验与预注册评测

**语言**：Python · JavaScript · C · LaTeX

---

<div align="center">
<sub>北陆先端科学技术大学院大学（JAIST）· 日本石川</sub>
</div>
