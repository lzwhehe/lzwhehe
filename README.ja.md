<div align="center">

<img src="assets/banner.svg?v=2" width="100%" alt="Liu Zhuowen — AI / Agent Security Researcher">

<a href="https://github.com/lzwhehe"><img src="https://img.shields.io/badge/中文-161b22?style=for-the-badge" alt="中文"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.en.md"><img src="https://img.shields.io/badge/English-161b22?style=for-the-badge" alt="English"></a> <a href="https://github.com/lzwhehe/lzwhehe/blob/main/README.ja.md"><img src="https://img.shields.io/badge/日本語-22d3ee?style=for-the-badge" alt="日本語"></a>

<a href="mailto:ryutakubunwork@gmail.com"><img src="https://img.shields.io/badge/Email-ryutakubunwork%40gmail.com-0b0f17?style=for-the-badge&labelColor=161b22&logo=gmail&logoColor=f5b041" alt="Email"></a>

</div>

<br>

こんにちは、劉卓文です。**北陸先端科学技術大学院大学（JAIST）先端科学技術専攻・サイバーセキュリティ研究室**の修士 2 年に在籍しています。

研究テーマは **SOC（セキュリティ運用）におけるエージェントのセキュリティ**で、LLM エージェントを実際のセキュリティ運用の現場に安全かつ確実に導入できるようにすることを目指しています。また、**中国の無形文化遺産の保護**にも取り組んでおり、最先端の AI 技術を活かして、伝統文化のデジタルな保存と継承を支えることに力を入れています。


## 🔬 Research

<img src="assets/card-now.svg" width="100%" alt="Forged logs vs. LLM triage agents">

<a href="https://github.com/lzwhehe/HESP"><img src="assets/card-hesp.svg?v=2" width="100%" alt="HESP"></a>

<a href="https://github.com/lzwhehe/benign-instruction-bench"><img src="assets/card-bench.svg" width="100%" alt="Passing the Test You Trained On"></a>

<a href="https://github.com/lzwhehe/kushulan-papercut-blora"><img src="assets/card-kushulan.svg" width="100%" alt="Safeguarding Intangible Heritage"></a>

<details>
<summary><b>各プロジェクトの概要</b></summary>

- **プレプリント・小型 LLM 分析エージェントに偽造ログを疑わせる学習は可能か**（筆頭著者、DOI 10.5281/zenodo.23311714）：22 のモデル構成（0.5B〜72B）で 1.1 万エピソードの偽造ログ・レッドチーム評価を実施。結論を出せる 4B〜72B のモデルはいずれも 36 件中 30〜36 件の攻撃を見逃し、その多くは矛盾する本物の記録をすでに確認していました。LoRA SFT + GRPO による微調整で、ホールドアウトの見逃しを 58/144 から 7/144 に削減。追加実験中です。
- **[HESP](https://github.com/lzwhehe/HESP)**（筆頭著者、arXiv:2609.33446）：「何を調べるか」と「いつ止めるか」をコントローラが担い、モデルは提案のみを行います。カウントした尤度表で Qwen2.5-7B の検証済み完了率を 0.125 から 1.000 に、コントローラ側の停止で Llama-3.1-8B を 0 から 0.917 に改善しました（事前登録研究 4 件、監査済み 7,272 エピソード）。
- **[Passing the Test You Trained On](https://github.com/lzwhehe/benign-instruction-bench)**（単著、arXiv:2610.03448）：AgentDojo / τ-bench の実際のツール出力を再生し、15 種のプロンプトインジェクション検知器と 2 種の LLM 判定器を再評価。BIPIA 首位の検知器は誤検知率 1% で AgentDojo の注入を約 2% しか検出できず、その学習データに BIPIA の入力 1,116 件が含まれていることも判明しました。
- **[庫淑蘭の彩貼り切り紙の生成](https://github.com/lzwhehe/kushulan-papercut-blora)**（共同筆頭著者、*npj Heritage Science* 査読中）：作品から色紙パレットと切り線を自動復元し、Qwen-Image-Edit をファインチューニング。線再現率 0.97。

</details>

## 🧰 Skills

<p align="center">
  <img src="https://img.shields.io/badge/Web_セキュリティ-f87171?style=for-the-badge" alt="Web セキュリティ">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Burp_Suite-161b22?style=for-the-badge&logo=burpsuite&logoColor=FF6633" alt="Burp Suite"> <img src="https://img.shields.io/badge/SQLMap-161b22?style=for-the-badge" alt="SQLMap"> <img src="https://img.shields.io/badge/Nmap-161b22?style=for-the-badge" alt="Nmap"> <img src="https://img.shields.io/badge/Xray-161b22?style=for-the-badge" alt="Xray"> <img src="https://img.shields.io/badge/OWASP_Top_10-161b22?style=for-the-badge&logo=owasp&logoColor=ffffff" alt="OWASP Top 10">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/エージェントツール-22d3ee?style=for-the-badge" alt="エージェントツール">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Claude_Code-161b22?style=for-the-badge&logo=claude&logoColor=D97757" alt="Claude Code"> <img src="https://img.shields.io/badge/Codex-161b22?style=for-the-badge" alt="Codex"> <img src="https://img.shields.io/badge/OpenCode-161b22?style=for-the-badge&logo=opencode&logoColor=ffffff" alt="OpenCode"> <img src="https://img.shields.io/badge/WorkBuddy-161b22?style=for-the-badge" alt="WorkBuddy"> <img src="https://img.shields.io/badge/Kimi_Code-161b22?style=for-the-badge&logo=kimi&logoColor=ffffff" alt="Kimi Code">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/開発-a78bfa?style=for-the-badge" alt="開発">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Vue-161b22?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue"> <img src="https://img.shields.io/badge/Node.js-161b22?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js"> <img src="https://img.shields.io/badge/vLLM-161b22?style=for-the-badge" alt="vLLM"> <img src="https://img.shields.io/badge/Ollama-161b22?style=for-the-badge&logo=ollama&logoColor=ffffff" alt="Ollama"> <img src="https://img.shields.io/badge/LoRA-161b22?style=for-the-badge" alt="LoRA"> <img src="https://img.shields.io/badge/Hyperledger_Fabric-161b22?style=for-the-badge" alt="Hyperledger Fabric">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/言語-f5b041?style=for-the-badge" alt="言語">&nbsp;&nbsp;<img src="https://img.shields.io/badge/Python-161b22?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python"> <img src="https://img.shields.io/badge/JavaScript-161b22?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript"> <img src="https://img.shields.io/badge/TypeScript-161b22?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript"> <img src="https://img.shields.io/badge/C-161b22?style=for-the-badge&logo=c&logoColor=A8B9CC" alt="C">
</p>

