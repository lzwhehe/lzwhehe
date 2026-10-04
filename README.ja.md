<div align="center">

<img src="assets/banner.svg?v=2" width="100%" alt="Liu Zhuowen — AI / Agent Security Researcher">

<a href="https://github.com/lzwhehe"><img src="https://img.shields.io/badge/中文-161b22?style=for-the-badge" alt="中文"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.en.md"><img src="https://img.shields.io/badge/English-161b22?style=for-the-badge" alt="English"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.ja.md"><img src="https://img.shields.io/badge/日本語-22d3ee?style=for-the-badge" alt="日本語"></a>

<a href="mailto:ryutakubunwork@gmail.com"><img src="https://img.shields.io/badge/Email-ryutakubunwork%40gmail.com-0b0f17?style=for-the-badge&labelColor=161b22&logo=gmail&logoColor=f5b041" alt="Email"></a>

</div>

<br>

こんにちは、劉卓文です。**北陸先端科学技術大学院大学（JAIST）先端科学技術専攻・サイバーセキュリティ研究室**の修士 2 年に在籍しています。

研究テーマは **SOC（セキュリティ運用）におけるエージェントのセキュリティ**で、LLM エージェントを実際のセキュリティ運用の現場に安全かつ確実に導入できるようにすることを目指しています。また、**中国の無形文化遺産の保護**にも取り組んでおり、最先端の AI 技術を活かして、伝統文化のデジタルな保存と継承を支えることに力を入れています。


## 🔬 Research

<img src="assets/card-now.svg" width="100%" alt="Now: premature verdicts under forged evidence">

<a href="https://github.com/lzwhehe/HESP"><img src="assets/card-hesp.svg?v=2" width="100%" alt="HESP"></a>

<a href="https://github.com/lzwhehe/benign-instruction-bench"><img src="assets/card-bench.svg" width="100%" alt="Passing the Test You Trained On"></a>

<a href="https://github.com/lzwhehe/kushulan-papercut-blora"><img src="assets/card-kushulan.svg" width="100%" alt="Safeguarding Intangible Heritage"></a>

<details>
<summary><b>各プロジェクトの概要</b></summary>

- **進行中・偽造証拠下での早すぎる判断**：0.5B〜72B のオープンモデル（Qwen2.5、Qwen3、Llama-3.1、Meta-SecAlign）で約 1 万エピソードを測定。結論を出せる大型モデルは、偽造ログのもとで 36 件の攻撃のうち 30〜36 件を良性と判定し、Qwen2.5-72B は平均 1.1 個の情報源しか確認せずに受け入れます。攻撃サンプルを一切使わない「裏付け重視」学習を事前登録中です。
- **[HESP](https://github.com/lzwhehe/HESP)**（筆頭著者、arXiv:2609.33446）：「何を調べるか」と「いつ止めるか」をコントローラが担い、モデルは提案のみを行います。カウントした尤度表で Qwen2.5-7B の検証済み完了率を 0.125 から 1.000 に、コントローラ側の停止で Llama-3.1-8B を 0 から 0.917 に改善しました（事前登録研究 4 件、監査済み 7,272 エピソード）。
- **[Passing the Test You Trained On](https://github.com/lzwhehe/benign-instruction-bench)**（論文草稿）：15 種のプロンプトインジェクション検知器の順位はベンチマーク間でほとんど一致せず（Kendall τ 0.01〜0.31）、スコアは主にベンチマークと学習データの近さを反映していました。
- **[庫淑蘭の彩貼り切り紙の生成](https://github.com/lzwhehe/kushulan-papercut-blora)**（共同筆頭著者、*npj Heritage Science* 査読中）：作品から色紙パレットと切り線を自動復元し、Qwen-Image-Edit をファインチューニング。線再現率 0.97。

</details>

## 🧰 Skills

<p align="center">
  <img src="https://img.shields.io/badge/Web_セキュリティ-f87171?style=for-the-badge" alt="Web セキュリティ">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Burp_Suite-161b22?style=for-the-badge&logo=burpsuite&logoColor=FF6633" alt="Burp Suite"> <img src="https://img.shields.io/badge/SQLMap-161b22?style=for-the-badge" alt="SQLMap"> <img src="https://img.shields.io/badge/Nmap-161b22?style=for-the-badge" alt="Nmap"> <img src="https://img.shields.io/badge/Xray-161b22?style=for-the-badge" alt="Xray"> <img src="https://img.shields.io/badge/OWASP_Top_10-161b22?style=for-the-badge&logo=owasp&logoColor=ffffff" alt="OWASP Top 10">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LLM_微調整・運用-a78bfa?style=for-the-badge" alt="LLM 微調整・運用">&nbsp;&nbsp;<img src="https://img.shields.io/badge/LoRA-161b22?style=for-the-badge" alt="LoRA"> <img src="https://img.shields.io/badge/PyTorch-161b22?style=for-the-badge&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"> <img src="https://img.shields.io/badge/vLLM-161b22?style=for-the-badge" alt="vLLM"> <img src="https://img.shields.io/badge/Ollama-161b22?style=for-the-badge&logo=ollama&logoColor=ffffff" alt="Ollama">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/エージェントツール-22d3ee?style=for-the-badge" alt="エージェントツール">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Claude_Code-161b22?style=for-the-badge&logo=claude&logoColor=D97757" alt="Claude Code"> <img src="https://img.shields.io/badge/Codex-161b22?style=for-the-badge" alt="Codex"> <img src="https://img.shields.io/badge/WorkBuddy-161b22?style=for-the-badge" alt="WorkBuddy"> <img src="https://img.shields.io/badge/Kimi_Code-161b22?style=for-the-badge&logo=kimi&logoColor=ffffff" alt="Kimi Code">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/言語-f5b041?style=for-the-badge" alt="言語">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Python-161b22?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python"> <img src="https://img.shields.io/badge/JavaScript-161b22?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/C-161b22?style=for-the-badge&logo=c&logoColor=A8B9CC" alt="C">
</p>

