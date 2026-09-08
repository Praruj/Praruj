<div align="right">
  <b>🌐 Language:</b>
  <a href="#user-content-english"><img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=googletranslate&logoColor=white" alt="English"/></a>
  <a href="#user-content-japanese"><img src="https://img.shields.io/badge/言語-日本語-red?style=flat-square&logo=googletranslate&logoColor=white" alt="Japanese"/></a>
</div>

<div align="center">

# Praruj Thapa · タパ プラルズ

### **AI/ML Engineer | Data Scientist**  
📍 Osaka, Japan · 🎓 Kyoto University of Advanced Science

> *"Data is just the world, speaking in numbers. I build systems that listen."*

[![Website](https://img.shields.io/badge/Portfolio-prarujthapa.com.np-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://prarujthapa.com.np/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Praruj_Thapa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prarujthapa)
[![GitHub](https://img.shields.io/badge/GitHub-PRaruj-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PRaruj)
[![Articles](https://img.shields.io/badge/Articles-Portfolio_Blog-0D9488?style=for-the-badge&logo=readme&logoColor=white)](https://www.prarujthapa.com.np/articles/)

</div>

<!-- TOP JAPANESE EXPANDER (1-Click Read in Japanese without scrolling) -->
<details id="top-japanese-summary">
<summary><b>🇯🇵 日本語でサクッと読む（クリックして展開 / Click to view quick Japanese summary）</b></summary>
<br>

> **「データとは、数字で語る世界そのものだ。私はそれに耳を傾けるシステムを作る。」**

- **所属**: フクシマガリレイ株式会社（時系列異常検知システムを開発。設備の故障兆候を**3〜4日前**に検知し、未然防止に貢献）
- **専門**: 時系列予測・異常検知、Vision Transformer (ViT) による画像分類、モンテカルロシミュレーション、RAG・ローカルLLM構築
- **学歴**: 京都先端科学大学（工学部 機械電気システム工学科 2025年卒）
- 📄 [詳しい日本語プロフィールと各プロジェクトの解説はこちら（下部へジャンプ）](#user-content-japanese)
<hr>
</details>

<div id="english"></div>

## ⚡ Overview

I design and deploy AI systems that **understand the past, predict the future, and take action** — bridging the gap between raw research and production engineering.

- 🏭 **Production ML at Scale:** At **Fukushima Galilei Co., Ltd.**, engineered an end-to-end time-series anomaly detection pipeline that flags critical equipment failures **3–4 days in advance**, turning noisy sensor streams into proactive, operator-ready interventions.
- 🎯 **Core Competencies:** Time-Series Forecasting · Vision Transformers (ViT) · Probabilistic Modeling & Simulation · Production RAG & Local LLMs.
- 🤝 Open to **AI/ML Engineering & Data Science roles, research collaborations, and graduate study opportunities**.

---

## 🛠️ Technical Stack

```python
stack = {
    "ML / Deep Learning": [
        "Time-Series Anomaly Detection", "Vision Transformers (ViT)",
        "Sentence-Transformers", "RAG (Retrieval-Augmented Generation)",
        "Local LLMs", "Semantic Search", "Cosine Similarity", "Model Evaluation"
    ],
    "Statistics & Simulation": [
        "Monte Carlo Simulation", "Probabilistic Forecasting",
        "Statistical Modeling", "Wilson Confidence Intervals"
    ],
    "Backend & APIs": [
        "Python", "FastAPI", "MySQL", "Caching Architectures", "REST APIs"
    ],
    "Frameworks & Tooling": [
        "PyTorch", "Hugging Face", "scikit-learn", "Pandas", "NumPy",
        "AWS (CLF)", "Docker", "Streamlit", "Gradio", "Git / GitHub Actions"
    ]
}
```

---

## 🔬 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔴 <a href="https://github.com/PRaruj/worldcup_prediction_2026">World Cup 2026 Prediction Engine</a></h3>
      <p>Tournament forecasting engine using <b>Monte Carlo simulation</b> across 10,000+ stochastic scenarios to yield probability distributions instead of naive single-point guesses.</p>
      <ul>
        <li>📊 <b>Brier Score:</b> <code>0.178</code> across all group stage matches</li>
        <li>🏆 <b>Validation:</b> Accurately forecast Spain as tournament champion</li>
        <li>⚙️ Wilson confidence intervals · Automated CI test suite · Bilingual docs</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/Simulation-Monte_Carlo-1E7E34?style=flat-square" alt="Monte Carlo"/>
        <img src="https://img.shields.io/badge/Scipy-Statistics-0054A6?style=flat-square" alt="Scipy"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🩸 <a href="https://github.com/PRaruj/vit-biomedical-finetuning">ViT Biomedical Image Classifier</a></h3>
      <p>Domain-adapted and fine-tuned <code>google/vit-base-patch16-224</code> on <b>46,000+ microscopic blood cell images</b> across 8 cell subtypes with diagnostic precision.</p>
      <ul>
        <li>🎯 <b>Test Accuracy:</b> <code>98.42%</code> · <b>Macro F1:</b> <code>98.13%</code></li>
        <li>🔬 Solved multi-class clinical imbalance via transfer learning</li>
        <li>⚡ Interactive Gradio app configured for Hugging Face Spaces</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
        <img src="https://img.shields.io/badge/Hugging_Face-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"/>
        <img src="https://img.shields.io/badge/Demo-Gradio-FF7C00?style=flat-square" alt="Gradio"/>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>☁️ <a href="https://github.com/PRaruj/aws_clf_co2_study_tool">AWS CLF-C02 Interactive Mastery Engine</a></h3>
      <p>Active-recall study web application engineered for the AWS Certified Cloud Practitioner exam, designed around spaced repetition and heuristic retention rather than passive review.</p>
      <p>
        <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JS"/>
        <img src="https://img.shields.io/badge/AWS-CLF--C02-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS"/>
        <img src="https://img.shields.io/badge/EdTech-Active_Recall-8A2BE2?style=flat-square" alt="Active Recall"/>
      </p>
    </td>
  </tr>
</table>

---

## 🧭 About & Journey

- 🎓 **Education:** B.E. in Electrical & Mechanical Systems — Kyoto University of Advanced Science (2025).
- 🗾 **Origin & Path:** Born in Nepal 🇳🇵 ➔ Studied engineering in Kyoto ⛩️ ➔ Building production ML in Osaka 🏙️.
- 🎙️ **Communication:** Former host of the *Guffadi Cast* podcast (2020–2022) — because solving data problems begins with listening to human needs.
- 🤝 **Leadership:** Founded a 30-member Rotaract Club in 2020 during lockdown to revitalize youth collaboration and community outreach.
- ✍️ **Writing:** Documenting machine learning experiments, research breakdowns, and analyses on my [portfolio blog](https://www.prarujthapa.com.np/articles/).

---

## 📈 GitHub Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PRaruj&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PRaruj&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Top Languages" />
</div>

---

<div id="japanese"></div>

## 🇯🇵 日本語プロフィール (Japanese Profile)

<div align="right">
  <a href="#user-content-english">⬆️ 英語に戻る (Back to English)</a>
</div>

### タパ プラルズ (Praruj Thapa)
**AI/MLエンジニア | データサイエンティスト · 大阪**

> *「データとは、数字で語る世界そのものだ。私はそれを聴くシステムを作る。」*

過去を理解し、未来を予測し、行動へとつなげるシステムを構築しています。MLモデル、時系列パイプライン、RAGシステム、そして現場で本当に役立つAIソフトウェアの開発に注力しています。

#### 💼 職務実績
- **フクシマガリレイ株式会社**: 時系列異常検知システムの開発・運用。産業用冷凍設備の故障予兆を**発生の3〜4日前**に検知し、オペレーターが事前に対処できるプロアクティブな保全体制を実現。

#### 🔬 主なプロジェクト
1. **🔴 [ワールドカップ2026予測エンジン](https://github.com/PRaruj/worldcup_prediction_2026)**  
   10,000回以上のモンテカルロシミュレーションを用いた確率的トーナメント予測。単一の当て推量ではなく、不確実性を織り込んだ確率分布を算出。（ブライアースコア: `0.178` / スペイン優勝を予測的中）
2. **🩸 [ViT 血液細胞画像分類](https://github.com/PRaruj/vit-biomedical-finetuning)**  
   4万6千枚超の血液顕微鏡画像を用いて `google/vit-base-patch16-224` をファインチューニング。全8クラスで**精度98.42%・マクロF1 98.13%**を達成。Hugging Face Spaces対応Gradioデモ付き。
3. **☁️ [AWS CLF-C02 アクティブリコール学習ツール](https://github.com/PRaruj/aws_clf_co2_study_tool)**  
   受動的な暗記ではなく能動的想起（Active Recall）を重視したAWS認定対策アプリ。

#### 👤 人物・バックグラウンド
- 🎓 **学歴**: 京都先端科学大学 工学部 機械電気システム工学科 卒業（2025年）
- 🗾 **歩み**: ネパール生まれ ➔ 京都で工学を専攻 ➔ 大阪でエンジニアとして活動中
- 🎙️ **発信・コミュニティ**: ポッドキャスト「Guffadi Cast」元ホスト（2020〜2022）、2020年ロータラクトクラブ創設（会員30名）。
- ✍️ **技術発信**: 自身のポートフォリオサイト（[prarujthapa.com.np/articles](https://www.prarujthapa.com.np/articles/)）にて機械学習の検証や技術記事を発信中。

📬 **Contact:** AI/MLエンジニア・データサイエンス職、共同研究、大学院進学の機会を積極的に探しています。ご連絡は [prarujthapa.com.np](https://prarujthapa.com.np/) または [LinkedIn](https://linkedin.com/in/prarujthapa) までお気軽にどうぞ！

---

<div align="center">
  <sub>Designed & Developed by Praruj Thapa · Osaka, Japan</sub>
</div>
