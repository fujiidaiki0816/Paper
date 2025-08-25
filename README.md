# Paper

## References

### Graph Neural Networks (GNN) – 基礎とサーベイ
- ** Z. Wu et al. (2021)**  
  *A comprehensive survey on graph neural networks.*  
  → GNN（グラフニューラルネットワーク）の基礎、構造、応用、課題を網羅的にまとめたサーベイ論文。

- ** M. Zhang and Y. Chen (2018)**  
  *Link prediction based on graph neural networks.*  
  → GNNをリンク予測タスクに応用し、従来のヒューリスティック手法を超える性能を示した研究。

- ** J. Gilmer et al. (2017)**  
  *Neural message passing for quantum chemistry.*  
  → 分子構造学習のための「Message Passing Neural Network (MPNN)」を提案し、以降のGNN研究の基盤となった。

- ** T. Kipf and M. Welling (2017)**  
  *Semi-supervised classification with graph convolutional networks (GCN).*  
  → GCNの代表的な論文。グラフ上での畳み込みを定義し、半教師あり分類に応用した。

---

### GNNを用いた推薦システム
- ** X. He et al. (2020)**  
  *LightGCN: Simplifying and powering graph convolution network for recommendation.*  
  → 特徴変換や非線形性を削除してシンプル化したLightGCNを提案。推薦性能を大幅に向上させた。

- ** W. Wang et al. (2021)**  
  *Denoising implicit feedback for recommendation.*  
  → インプリシットフィードバックに含まれるノイズを低減し、推薦性能を改善する手法を提案。

- ** X. Wang et al. (2019)**  
  *Neural graph collaborative filtering (NGCF).*  
  → ユーザ–アイテム関係に高次の接続情報を組み込み、推薦性能を強化するNGCFを提案。

- ** J. Wu et al. (2021)**  
  *Self-supervised graph learning for recommendation (SGL).*  
  → グラフベース推薦に自己教師あり学習（コントラスト学習）を導入した先駆的研究。

- ** J. Yu et al. (2022)**  
  *Are graph augmentations necessary? Simple graph contrastive learning for recommendation.*  
  → 複雑な拡張を使わずに、シンプルなコントラスト学習で十分高性能が得られることを示した。

- ** H. Ye et al. (2023)**  
  *Towards robust neural graph collaborative filtering via structure denoising and embedding perturbation.*  
  → グラフ構造のノイズ除去や埋め込みの摂動を行い、頑健な推薦を実現する手法。

- ** Z. Zhou et al. (2023)**  
  *Combating bilateral edge noise for robust link prediction.*  
  → グラフのリンク予測において、両側のエッジノイズを抑制することでモデルのロバスト性を高めた。

---

### Collaborative Filtering – 基礎
- ** I. Gunes et al. (2014)**  
  *Shilling attacks against recommender systems: a comprehensive survey.*  
  → 推薦システムに対するシリング攻撃を網羅的に整理したサーベイ論文。

- ** Y. Hu, Y. Koren, and C. Volinsky (2008)**  
  *Collaborative filtering for implicit feedback datasets.*  
  → 評価値ではなく、クリックや閲覧などのインプリシットフィードバックを扱う初期の研究。

- ** X. He et al. (2017)**  
  *Neural collaborative filtering (NCF).*  
  → 行列分解とニューラルネットを組み合わせたNeural CFを提案し、新たな推薦モデルの方向性を示した。

- ** D. Liang et al. (2018)**  
  *Variational autoencoders for collaborative filtering (Mult-VAE).*  
  → VAE（変分オートエンコーダ）を推薦に適用し、ユーザ嗜好を潜在変数としてモデル化。

- ** P. Resnick et al. (1994)**  
  *GroupLens: an open architecture for collaborative filtering of netnews.*  
  → 協調フィルタリングの初期の代表的システムであるGroupLensを提案。

- ** J. Breese et al. (1998)**  
  *Empirical analysis of predictive algorithms for collaborative filtering.*  
  → さまざまなCFアルゴリズムを実証的に比較した初期の研究。

- ** X. He et al. (2017)**  
  *Neural collaborative filtering (extended version).*  
  → WWW’17で発表されたNeural CFの詳細版。

- ** S. Rendle et al. (2012)**  
  *Bayesian Personalized Ranking (BPR).*  
  → ペアワイズランキング最適化に基づく代表的手法で、インプリシットフィードバックに広く利用される。
