<div align="center">

<img src="assets/banner.svg?v=2" width="100%" alt="Liu Zhuowen — AI / Agent Security Researcher">

<a href="https://github.com/lzwhehe"><img src="https://img.shields.io/badge/中文-161b22?style=for-the-badge" alt="中文"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.en.md"><img src="https://img.shields.io/badge/English-161b22?style=for-the-badge" alt="English"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.ja.md"><img src="https://img.shields.io/badge/日本語-22d3ee?style=for-the-badge" alt="日本語"></a>

<a href="mailto:ryutakubunwork@gmail.com"><img src="https://img.shields.io/badge/Email-ryutakubunwork%40gmail.com-0b0f17?style=for-the-badge&labelColor=161b22&logo=gmail&logoColor=f5b041" alt="Email"></a> <a href="https://arxiv.org/abs/2609.33446"><img src="https://img.shields.io/badge/arXiv-2609.33446-0b0f17?style=for-the-badge&labelColor=161b22&logo=arxiv&logoColor=f87171" alt="arXiv"></a> <a href="https://doi.org/10.5281/zenodo.23133690"><img src="https://img.shields.io/badge/DOI-zenodo.23133690-0b0f17?style=for-the-badge&labelColor=161b22&logo=zenodo&logoColor=22d3ee" alt="DOI"></a>

</div>

<br>

こんにちは、劉卓文です。**北陸先端科学技術大学院大学（JAIST）先端科学技術専攻・サイバーセキュリティ研究室**の修士 2 年に在籍しています。

研究テーマは **SOC（セキュリティ運用）におけるエージェントのセキュリティ**で、LLM エージェントを実際のセキュリティ運用の現場に安全かつ確実に導入できるようにすることを目指しています。また、**中国の無形文化遺産の保護**にも取り組んでおり、最先端の AI 技術を活かして、伝統文化のデジタルな保存と継承を支えることに力を入れています。

## 🎯 希望職種

**2027 年卒**（2027 年 3 月修士修了予定）。セキュリティ / AI セキュリティ職を探しています：

<img src="assets/jobs-ja.svg" width="100%" alt="🎯 希望職種">

## 🔬 Research

<img src="assets/card-now.svg" width="100%" alt="Now: premature verdicts under forged evidence">

<a href="https://github.com/lzwhehe/HESP"><img src="assets/card-hesp.svg" width="100%" alt="HESP"></a>

<a href="https://github.com/lzwhehe/benign-instruction-bench"><img src="assets/card-bench.svg" width="100%" alt="Passing the Test You Trained On"></a>

<a href="https://github.com/lzwhehe/kushulan-papercut-blora"><img src="assets/card-kushulan.svg" width="100%" alt="Safeguarding Intangible Heritage"></a>

<details>
<summary><b>各プロジェクトの概要</b></summary>

- **進行中・偽造証拠下での早すぎる判断**：0.5B〜72B のオープンモデル（Qwen2.5、Qwen3、Llama-3.1、Meta-SecAlign）で約 1 万エピソードを測定。結論を出せる大型モデルは、偽造ログのもとで 36 件の攻撃のうち 30〜36 件を良性と判定し、Qwen2.5-72B は平均 1.1 個の情報源しか確認せずに受け入れます。攻撃サンプルを一切使わない「裏付け重視」学習を事前登録中です。
- **[HESP](https://github.com/lzwhehe/HESP)**（筆頭著者）：モデルはログを読むだけ、判断はコントローラが行います。ログ形式の変更後も「7B が読み、コントローラが判断」で 48 件すべてを解決。「リーダー信頼」ルールにより、検証したすべての攻撃で見逃しを 0 にしました。
- **[Passing the Test You Trained On](https://github.com/lzwhehe/benign-instruction-bench)**（論文草稿）：15 種のプロンプトインジェクション検知器の順位はベンチマーク間でほとんど一致せず（Kendall τ 0.01〜0.31）、スコアは主にベンチマークと学習データの近さを反映していました。
- **[庫淑蘭の彩貼り切り紙の生成](https://github.com/lzwhehe/kushulan-papercut-blora)**（共同筆頭著者、*npj Heritage Science* 査読中）：作品から色紙パレットと切り線を自動復元し、Qwen-Image-Edit をファインチューニング。線再現率 0.97。

</details>

## 🧰 Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,git,latex,js,c&theme=dark" alt="Python · PyTorch · Git · LaTeX · JavaScript · C">
</p>

| 分野 | 使っているもの |
| :-- | :-- |
| **Agent&nbsp;セキュリティ** | 間接プロンプトインジェクション・証拠偽造・適応的攻撃・リーダー信頼 / 複数情報源による裏付け・OWASP LLM Top 10 |
| **評価** | 事前登録実験・先行書き込みログと独立検証器・AgentDojo・τ-bench・BIPIA・SigmaHQ / ATT&CK |
| **LLM** | vLLM・Ollama・Qwen2.5 / Qwen3 / Llama-3.1 のローカル運用・MCP・LoRA ファインチューニング（Qwen-Image-Edit、SDXL） |
| **Web&nbsp;セキュリティ** | OWASP Top 10・Burp Suite・SQLMap・Nmap・Xray |

<div align="center">
<br>
<sub>北陸先端科学技術大学院大学（JAIST）· 石川県 · <i>let the model read, not decide.</i></sub>
</div>
