<p align="right"><sub><a href="#user-content-english">English</a> · <a href="#user-content-japanese">日本語</a></sub></p>

<div id="english"></div>

### Praruj Thapa

AI/ML engineer and data scientist at Fukushima Galilei. I build systems that turn noisy data into decisions people can trust; my current one flags equipment failures days before they happen.

> *All models are wrong, but some are useful.* — George Box

**Selected work**

- [Hybrid digital twin for jet-engine wear](https://github.com/Praruj/turbofan-digital-twin): gas-path physics, a Kalman-filter bank and ML on NASA C-MAPSS to predict remaining useful life; hybrid RMSE 12.3 (ML alone 13.8, physics alone 16.4), and with only 5 failed engines to learn from the physics model wins (20.9 vs 25.7) · [case study](https://www.prarujthapa.com.np/turbofan/)
- [Industrial anomaly detection on the edge](https://github.com/Praruj/industrial-edge-anomaly): visual inspection and vibration monitoring, int8 at 89 ms per image on one CPU thread · [case study](https://www.prarujthapa.com.np/edge/)
- [Bilingual product search and recommendation](https://github.com/Praruj/bilingual-product-search): Japanese/English search on Amazon ESCI with BM25, multilingual E5, hybrid retrieval and reranking, then both models fine-tuned on ESCI: NDCG@10 0.595 (JA) / 0.576 (EN), up from 0.567 / 0.560 off the shelf; hybrid search 32 ms per query on CPU; also tested an open LLM (Qwen2.5-7B, free Colab) as a relevance judge: weak agreement with human labels (Cohen's κ 0.16–0.21), and a reranker distilled from its labels did worse than one trained on human labels · [case study](https://www.prarujthapa.com.np/search/)
- [Stress detection from wearable sensors](https://github.com/Praruj/stress-detection): 92.7% accuracy on people the model never saw · [case study](https://www.prarujthapa.com.np/stress/)
- [Decision phenotypes of addiction](https://github.com/Praruj/addiction-decision-phenotypes): computational psychiatry on 12,883 Iowa Gambling Task choices of heroin users, amphetamine users and controls; reinforcement-learning models (PVL-Delta, VPP, ORL) vs a GRU, which predicted unseen people's next 40 choices better than every psychology model (69% of people); plus an LLM agent playing the same task with and without chain-of-thought · [case study](https://www.prarujthapa.com.np/addiction/)
- [Compulsivity and planning: a pre-registered replication](https://github.com/Praruj/compulsivity-goal-directed): independent replication of Gillan et al. (2016) on 1,961 people; a mixed model written from scratch reproduces the published effect (−0.0585 vs −0.058), it replicates in a new sample (pooled z = −5.07), alcohol is not a separate signal, and a reaction-time marker halves the sample needed · [case study](https://www.prarujthapa.com.np/compulsivity/)
- [The Empathy Map](https://github.com/Praruj/empathy-map): an open-source sentiment model finds the reply after which an upset person's mood turns, and names the technique; runs offline, served as a static site; sample conversations are made up, so it is a demo, not a study · [live](https://praruj.github.io/empathy-map/)
- [Blood-cell classification with a vision transformer](https://github.com/Praruj/vit-biomedical-finetuning): 98.4% across eight cell types, and where the 73 errors fall · [case study](https://www.prarujthapa.com.np/blood-cells/)
- [World Cup 2026 forecasts](https://github.com/Praruj/worldcup_prediction_2026): Monte Carlo simulation, Brier score 0.178 · [case study](https://www.prarujthapa.com.np/worldcup/) · [live](https://www.prarujthapa.com.np/worldcup/worldcup.html)
- [Vision transformer experiments](https://github.com/Praruj/vision-transformer-projects): knowledge distillation and DETR object detection

**Writing**

- [Detecting stress from wearable sensors, in people the model has never seen](https://www.prarujthapa.com.np/stress/)
- [Why predictive maintenance models fail without domain constraints](https://www.prarujthapa.com.np/articles/predictive-maintenance-domain-constraints.html)
- [I built a game for 142 children I never met. Here's what their taps said](https://www.prarujthapa.com.np/articles/game-hiroba-play-data.html)
- [All articles](https://www.prarujthapa.com.np/articles/)

<sub>Python · PyTorch · scikit-learn · time series · physics-based modelling &amp; digital twins · search &amp; recommendation · computer vision · RAG · computational psychiatry</sub><br>
<sub>Kyoto University of Advanced Science, B.E. 2025 · AWS Certified AI Practitioner · AWS Certified Cloud Practitioner</sub>

[prarujthapa.com.np](https://prarujthapa.com.np/) · [LinkedIn](https://www.linkedin.com/in/praruj-thapa/) · [thapa.praruj@gmail.com](mailto:thapa.praruj@gmail.com)

<br>

<div id="japanese"></div>

### タパ プラルズ

フクシマガリレイ株式会社で働くAI・機械学習エンジニア／データサイエンティスト。ノイズの多いデータを、信頼できる判断へと変えるシステムを作っています。

- **所属**: フクシマガリレイ株式会社（時系列異常検知システムを開発。設備の故障兆候を3〜4日前に検知）
- **専門**: 時系列・センサーデータの機械学習、物理モデリング・デジタルツイン、検索・レコメンド、Vision Transformer、モンテカルロシミュレーション、RAG・ローカルLLM
- **学歴**: 京都先端科学大学 工学部 機械電気システム工学科（2025年卒）

> *すべてのモデルは間違っているが、中には役に立つものもある。* — ジョージ・ボックス

**主な取り組み**

- [ジェットエンジン劣化のハイブリッド・デジタルツイン](https://github.com/Praruj/turbofan-digital-twin)：ガスパス物理モデル・カルマンフィルタ群・機械学習をNASA C-MAPSSで組み合わせ、残存寿命を予測。ハイブリッドのRMSEは12.3（MLのみ13.8、物理のみ16.4）。故障エンジンが5台しかない場合は物理モデルが優位（20.9 vs 25.7） · [解説](https://www.prarujthapa.com.np/turbofan/)
- [エッジで動く産業向け異常検知](https://github.com/Praruj/industrial-edge-anomaly)：外観検査と振動監視、int8化で1スレッド1枚89 ms · [解説](https://www.prarujthapa.com.np/edge/)
- [日英バイリンガル商品検索・レコメンド](https://github.com/Praruj/bilingual-product-search)：AmazonのESCIデータでBM25・多言語E5・ハイブリッド検索・再ランキングを比較し、両モデルをESCIでファインチューニング。NDCG@10 0.595（日本語）・0.576（英語）（既製モデルでは0.567・0.560）、ハイブリッド検索はCPUで1クエリ32 ms。オープンLLM（Qwen2.5-7B、無料Colab）による関連度判定も検証し、人手ラベルとの一致は低く（κ 0.16〜0.21）、LLMラベルで学習した再ランキングは人手ラベル版に劣ることを確認 · [解説](https://www.prarujthapa.com.np/search/)
- [ウェアラブルセンサーによるストレス検出](https://github.com/Praruj/stress-detection)：学習に使っていない人物で精度92.7% · [解説](https://www.prarujthapa.com.np/stress/)
- [依存症の意思決定フェノタイプ](https://github.com/Praruj/addiction-decision-phenotypes)：ヘロイン使用者・アンフェタミン使用者・健常者によるアイオワ・ギャンブリング課題12,883回の選択で計算論的精神医学を実践。強化学習モデル（PVL-Delta・VPP・ORL）とGRUを比較し、GRUが未知の人物の次の40回の選択をすべての心理学モデルより正確に予測（69%の人物）。同じ課題を思考の連鎖あり・なしでプレイするLLMエージェントも構築 · [解説](https://www.prarujthapa.com.np/addiction/)
- [強迫性と計画性：事前登録した再現研究](https://github.com/Praruj/compulsivity-goal-directed)：Gillan ら（2016）を1,961名で独立に再現。一から実装した混合モデルで論文の効果を再現（−0.0585 vs −0.058）し、新しいサンプルでも再現（統合 z = −5.07）。飲酒は独立した信号ではなく、反応時間の指標で必要なサンプル数が半減 · [解説](https://www.prarujthapa.com.np/compulsivity/)
- [The Empathy Map](https://github.com/Praruj/empathy-map)：オープンソースの感情分析モデルで、相手の気持ちが上向いた返事を見つけ、その技法を判定。処理はオフライン、静的サイトで公開。サンプル会話は架空のため、研究ではなくデモ · [ライブ](https://praruj.github.io/empathy-map/)
- [Vision Transformerによる血液細胞分類](https://github.com/Praruj/vit-biomedical-finetuning)：8種類で精度98.4%、誤り73件の分析 · [解説](https://www.prarujthapa.com.np/blood-cells/)
- [ワールドカップ2026予測](https://github.com/Praruj/worldcup_prediction_2026)：モンテカルロシミュレーション、ブライアースコア0.178 · [解説](https://www.prarujthapa.com.np/worldcup/) · [ライブ](https://www.prarujthapa.com.np/worldcup/worldcup.html)
- [Vision Transformerの実験](https://github.com/Praruj/vision-transformer-projects)：知識蒸留とDETRによる物体検出

[prarujthapa.com.np](https://prarujthapa.com.np/) · [LinkedIn](https://www.linkedin.com/in/praruj-thapa/) · [thapa.praruj@gmail.com](mailto:thapa.praruj@gmail.com)
