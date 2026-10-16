<div align="right">
  <a href="#user-content-english"><img src="https://img.shields.io/badge/Language-English-blue?style=flat-square&logo=googletranslate&logoColor=white" alt="English"/></a>
  <a href="#user-content-japanese"><img src="https://img.shields.io/badge/言語-日本語-red?style=flat-square&logo=googletranslate&logoColor=white" alt="Japanese"/></a>
</div>

<div align="center">

# Praruj Thapa · タパ プラルズ

**AI/ML Engineer · Time-series & sensor ML · Computer Vision**<br>
📍 Osaka, Japan · Fluent in English & 日本語

> *"All models are wrong, but some are useful."* — George Box

[![Portfolio](https://img.shields.io/badge/Portfolio-prarujthapa.com.np-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://prarujthapa.com.np/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Praruj_Thapa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/praruj-thapa/)
[![Articles](https://img.shields.io/badge/Writing-Articles-0D9488?style=for-the-badge&logo=readme&logoColor=white)](https://www.prarujthapa.com.np/articles/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thapa.praruj@gmail.com)

| ⏱️ **3–4 days** | 🫀 **92.7%** | 🩸 **98.4%** | 🏆 **0.178** |
|:---:|:---:|:---:|:---:|
| early warning of equipment failure in production | stress detection on people a model never saw | ViT blood-cell accuracy, 8 classes | Brier score, World Cup 2026 forecasts |

</div>

<div id="english"></div>

## 💼 What I do

I turn **noisy real-world signals into decisions people can trust**: from industrial sensor streams
at work to physiological signals and images in my own projects. I care as much about *honest
evaluation* as about the model, and I ship tested, reproducible code.

- 🏭 **Production:** At **Fukushima Galilei Co., Ltd.** I built an end-to-end time-series anomaly
  detection pipeline that flags critical equipment failures **3–4 days in advance**.
- 🎯 **Focus:** time-series & sensor ML · computer vision with transformers · probabilistic modelling ·
  RAG & local LLMs.
- 🤝 **Open to** AI/ML engineering and data-science roles, research collaborations and graduate study.

---

## 🔬 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🫀 <a href="https://github.com/Praruj/stress-detection">Stress Detection from Wearable Sensors</a></h3>
      <p>CNN-LSTM and a <b>hybrid deep + physiological-feature model</b> on chest ECG, EDA and breathing (WESAD), evaluated <b>leave-one-subject-out</b>, so every result is on an unseen person.</p>
      <ul>
        <li>📊 <b>92.7%</b> stress detection · 4-state accuracy <b>19% → 83%</b> vs. my first version</li>
        <li>🧪 Ablation study, 5-seed ensembles, honest validation-vs-test reporting</li>
        <li>⚙️ pytest + GitHub Actions CI · one-click Colab reproduction</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
        <img src="https://img.shields.io/badge/Time--Series-CNN--LSTM-6E40C9?style=flat-square" alt="CNN-LSTM"/>
        <img src="https://img.shields.io/badge/CI-tested-2EA44F?style=flat-square&logo=githubactions&logoColor=white" alt="CI"/>
      </p>
      <p><a href="https://www.prarujthapa.com.np/stress/">Case study ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🩸 <a href="https://github.com/PRaruj/vit-biomedical-finetuning">ViT Biomedical Image Classifier</a></h3>
      <p>Fine-tuned <code>google/vit-base-patch16-224</code> on <b>46,000+ microscopy images</b> of blood cells across 8 subtypes.</p>
      <ul>
        <li>🎯 <b>Test accuracy</b> <code>98.42%</code> · <b>Macro-F1</b> <code>98.13%</code></li>
        <li>🔬 Handled multi-class clinical imbalance with transfer learning</li>
        <li>⚡ Interactive Gradio app for Hugging Face Spaces</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
        <img src="https://img.shields.io/badge/Hugging_Face-Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
        <img src="https://img.shields.io/badge/Demo-Gradio-FF7C00?style=flat-square" alt="Gradio"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏆 <a href="https://github.com/PRaruj/worldcup_prediction_2026">World Cup 2026 Prediction Engine</a></h3>
      <p>Tournament forecasting with <b>Monte Carlo simulation</b> over 10,000+ scenarios, producing probability distributions instead of single-point guesses.</p>
      <ul>
        <li>📊 <b>Brier score</b> <code>0.178</code> across group-stage matches</li>
        <li>🏆 Forecast Spain as champion</li>
        <li>⚙️ Wilson confidence intervals · automated CI · bilingual docs</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/Simulation-Monte_Carlo-1E7E34?style=flat-square" alt="Monte Carlo"/>
      </p>
      <p><a href="https://www.prarujthapa.com.np/worldcup/worldcup.html">Live demo ↗</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>👁️ <a href="https://github.com/Praruj/vision-transformer-projects">Vision Transformer Explorations</a></h3>
      <p>Transformer architectures for detection and classification, deployed as zero-install web apps.</p>
      <ul>
        <li>🧠 <b>Knowledge distillation:</b> ViT accuracy <code>11.6%</code> → <code>37.6%</code> (37 classes)</li>
        <li>🦺 <b>DETR</b> hardhat detection, final training loss <code>1.35</code>, no NMS</li>
        <li>⚡ Both models on Gradio / Hugging Face Spaces</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Computer_Vision-Transformers-4B0082?style=flat-square" alt="Computer Vision"/>
        <img src="https://img.shields.io/badge/Knowledge_Distillation-008080?style=flat-square" alt="Knowledge Distillation"/>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Languages** | Python · SQL |
| **ML / DL** | PyTorch · scikit-learn · Hugging Face · time-series · computer vision · NLP |
| **GenAI** | LangChain · RAG · local LLMs |
| **Data** | pandas · NumPy · SciPy · statistical modelling · Monte Carlo simulation |
| **Backend & apps** | FastAPI · REST APIs · MySQL · Streamlit · Gradio |
| **MLOps** | Docker · AWS · Git · GitHub Actions · pytest |

<sub>☁️ AWS Certified AI Practitioner (2026)</sub>

---

## 🧭 About

- 🎓 **B.E. Electrical & Mechanical Systems**, Kyoto University of Advanced Science (2025)
- 🗾 Born in Nepal 🇳🇵 → studied engineering in Kyoto ⛩️ → building production ML in Osaka 🏙️
- 🎙️ Former host of the *Guffadi Cast* podcast (2020–2022) · 🤝 founded a 30-member Rotaract Club (2020)
- ✍️ I write about ML experiments and what they taught me on my [blog](https://www.prarujthapa.com.np/articles/), most recently
  [*Detecting Stress from Wearable Sensors*](https://www.prarujthapa.com.np/stress/) and
  [*Why Predictive Maintenance Models Fail Without Domain Constraints*](https://www.prarujthapa.com.np/articles/predictive-maintenance-domain-constraints.html)

---

<div id="japanese"></div>

## 🇯🇵 日本語プロフィール

<div align="right"><a href="#user-content-english">⬆️ English</a></div>

**タパ プラルズ (Praruj Thapa)** · AI/MLエンジニア · 大阪

- **所属**: フクシマガリレイ株式会社（時系列異常検知システムを開発。設備の故障兆候を**3〜4日前**に検知）
- **専門**: 時系列・センサーデータの機械学習、Vision Transformer、モンテカルロシミュレーション、RAG・ローカルLLM
- **学歴**: 京都先端科学大学 工学部 機械電気システム工学科（2025年卒）

> *「すべてのモデルは間違っているが、中には役に立つものもある。」* — ジョージ・ボックス

ノイズの多い現実のデータを、信頼できる判断へと変えるシステムを作っています。モデルだけでなく、正直な評価と再現可能でテストされたコードを重視しています。

#### 💼 職務実績
- **フクシマガリレイ株式会社**: 時系列異常検知パイプラインを開発。産業用冷凍設備の故障予兆を**3〜4日前**に検知し、事前対応を可能に。

#### 🔬 主なプロジェクト
1. **🫀 [ウェアラブルセンサーによるストレス検出](https://github.com/Praruj/stress-detection)**: 胸部のECG・EDA・呼吸信号に対し、CNN-LSTMと深層学習＋生理学的特徴量のハイブリッドモデルを構築。学習に使っていない人物のみで評価し、ストレス検出**92.7%**、4状態の精度を初版の19%から**83%**へ改善。CI・Colab再現対応。
2. **🩸 [ViT 血液細胞画像分類](https://github.com/PRaruj/vit-biomedical-finetuning)**: 4万6千枚超の顕微鏡画像で `google/vit-base-patch16-224` をファインチューニング。8クラスで**精度98.42%・マクロF1 98.13%**。
3. **🏆 [ワールドカップ2026予測エンジン](https://github.com/PRaruj/worldcup_prediction_2026)**: 10,000回以上のモンテカルロシミュレーションによる確率的予測。ブライアースコア `0.178`、スペイン優勝を予測。
4. **👁️ [Vision Transformer プロジェクト](https://github.com/Praruj/vision-transformer-projects)**: 知識蒸留でViTの精度を `11.6%` → `37.6%` に向上。DETRによるヘルメット検出（最終Loss `1.35`）。

#### 👤 バックグラウンド
- 🎓 京都先端科学大学 工学部 機械電気システム工学科 卒業（2025年）
- 🗾 ネパール生まれ → 京都で工学を専攻 → 大阪でMLエンジニアとして活動中
- 🎙️ ポッドキャスト「Guffadi Cast」元ホスト（2020〜2022）· 🤝 ロータラクトクラブ創設（2020年、会員30名）
- ✍️ [ポートフォリオブログ](https://www.prarujthapa.com.np/articles/)で機械学習の検証記事を発信中

📬 AI/MLエンジニア・データサイエンス職、共同研究、大学院進学の機会を探しています。[prarujthapa.com.np](https://prarujthapa.com.np/) または [LinkedIn](https://www.linkedin.com/in/praruj-thapa/) からお気軽にご連絡ください。

---

<div align="center"><sub>Praruj Thapa · Osaka, Japan</sub></div>
