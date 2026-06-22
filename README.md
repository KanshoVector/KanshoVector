# 佐藤怜央 (Reo Sato / KanshoVector)
**データサイエンス学科（学部3年）｜構造の抽象化 × システム的レバレッジ × 規律による品質保証**

特定のドメインや個別技術への固執を排し、あらゆる対象を「構造と制約」として抽象化して捉えるアプローチを重視しています。
システム上の不条理や仕様の穴（ボトルネック）をメタ視点で見つけ出し、AIや数理モデルを血液としてレバレッジ（自動化・最適化）をかける一方で、人間の意志や手癖に頼らない「実務耐えしうる規律（フォールバック・パイプライン）」を組み込むことで、圧倒的な生産性と堅牢性を両立させることを思想としています。

---

## 🛠️ Core Philosophy
- **Leverage & Abstract**: ドメインの泥臭い暗記や労働を拒絶し、共通する構造を抜き出して最小コストで最大効率を生み出す。
- **Rigid Architecture**: 外部APIの破綻や環境の不確実性を前提とし、システム全域に自動的なフォールバックと型安全な規律を配備する。
- **Meta-Prompting**: LLMをブラックボックスなコード生成器として使わず、仕様策定から段階的実装までのプロセスをメタプロンプトで制御し、負債を量産させない。

---

## 🚀 Projects

### 📊 Bayesian Disaster Priority — 不確実性の可視化とシステムフォールバック
性質の異なる複数の数理手法を統合し、個人の経験則に依存しない意思決定の「根拠と揺らぎ（HDI）」を可視化するシステム。
- **Abstract & Leverage**: 統計（MCMC）、因果（ベイズネットワーク）、分類（ナイーブベイズ）のアンサンブル構成を設計し、単一モデルの限界を相互に補完する構造を構築。
- **Quality Assurance**: 高度な計算パーツが環境制約やメモリ枯渇で破綻した際、システムを停止させず簡易数式へ自動切り替えするフォールバック構造を全域に実装。
- **Links**: [GitHub](https://github.com/KanshoVector/bayesian-disaster-priority) / [Production](https://bayesian-disaster-priority-wnttn3ck54r433xbajyknx.streamlit.app/)

### 🗺️ ResQGo — 空間演算の正規化とデータの完全秘匿
大規模支援が届かない被災者の微細なSOSとボランティアをリアルタイムに繋ぐ位置情報Webアプリケーション。
- **Abstract & Leverage**: 空間演算（PostGIS）におけるGeoJSONやEWKB hex等の形式混在に対し、データ取得の前段で一元化する座標正規化関数を自作し、経路リンク生成を構造的に担保。
- **Quality Assurance**: Server ActionsとRPCを組み合わせ、クライアント側にテーブルを直接触らせないアーキテクチャを採用。主キーおよび個人情報をサーバー側で完全に秘匿。
- **Links**: [GitHub](https://github.com/KanshoVector/resqgo) / [Production](https://resqgo.vercel.app/)

### 🤖 Cyber-Physical Tremor Simulator — 臨床データの物理再現
臨床データの支配的周波数を解析し、ロボット制御によって物理世界に微細な震えを再現するサイバーフィジカルシステム（CPS）。
- **Abstract & Leverage**: 生体信号というノイズの多い波形データを周波数領域に抽象化し、ハードウェアの制御スタックへ正確にマッピングするパイプラインを設計。
- **Links**: [GitHub](https://github.com/KanshoVector/cyber-physical-tremor-simulator)

### 📝 Nostalgic Bulletin Board — ゼロベースでのWeb3層構造構築
フレームワークのブラックボックス（自動生成）に依存せず、Webの基本原則を自力で再現した位置情報連動型メディアログ。
- **Abstract & Leverage**: 認証、セッション管理、複雑なCRUDをライブラリなしで構築。将来的なグループ拡張を見据え、公開範囲の動的制御をDB設計レベルでモジュール化。
- **Links**: [GitHub](https://github.com/KanshoVector/Nostalgic-bulletin-board) / [Production](https://muds.gdl.jp/~s2422073/login.php)

---

## 🏆 Kaggle & Data Science — [Kaggle Profile](https://www.kaggle.com/oreo01mofu)
単なるスコア追従のチューニングではなく、市場や環境特有のノイズと評価指標の制約を「構造」として読み解き、ロジックへ還元するプロセスを検証。

- **Hull Tactical (Featured/時系列予測 — 暫定上位2.7％)**
  トレンド分類（方向性）と投資配分回帰（確信度）を機能分離したアンサンブルモデルを設計。AIの過剰判定に対してKelly基準によるブレーキを実装。データリークを徹底的に排除した厳密な時系列クロスバリデーションパイプラインを構築。
- **Road Accident Risk (予測)**
  地理的・環境的制約から本質的な特徴量を抽出する特徴量エンジニアリングと、予測根拠の透明性を担保したモデル設計。

---

## 🧪 Languages and Tools
特定の言語依存を避け、アーキテクチャの要件（型安全、数理モデリング、データ永続化）に応じて適材適所で選択・制御しています。

<p align="left"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="40" height="40"/> 
<img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
</p>
