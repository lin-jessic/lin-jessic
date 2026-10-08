<p align="right"><a href="https://github.com/lin-jessic/lin-jessic/blob/main/README.md">繁體中文</a> &nbsp; · &nbsp; <a href="https://github.com/lin-jessic/lin-jessic/blob/main/en/README.md">English</a> &nbsp; · &nbsp; <strong>日本語</strong></p>

<p align="center"><img src="../assets/banner.svg" width="100%" alt="林冠妤 Guan-Yu Lin" /></p>

<p align="center"><sub>COMPUTER SYSTEMS · BIOMEDICAL IMAGING · RESEARCH</sub></p>

## 自己紹介

私は**林冠妤（Guan-Yu Lin）**です。**台湾**出身で、現在は**長庚大学（台湾）の情報工学系**で学んでいます。以前は生物や化学工学を学んでおり、情報工学への転向後、**ハードウェアとソフトウェアの統合、組込みシステム、AI、生体医用画像解析**に関心を持つようになりました。

身近な課題を出発点として、実装・テスト・研究を通じて技術が実際のシステムでどのように動くのかを理解することを大切にしています。

## 学歴

- **高校：丹鳳高級中学（台湾）** — 第四類組（生物系）
- **大学1年：大同大学（台湾）** — 化学工学・バイオテクノロジー学科
- **大学2年～現在：長庚大学（台湾）** — 情報工学系。主な関心分野はコンピュータシステムと生体医用画像


[ESP32 自動ペット給餌器](https://github.com/lin-jessic/esp32-pet-feeder-archive)は、大同大学の1年次に制作した初期の作品です。センサーの読み取りからプログラムによる判断、モーターの制御まで取り組んだことで、情報工学をもっと学びたいと思うようになり、転学を決めるきっかけの一つになりました。最近、当時の原本を見つけたため、記録として公開しました。

### プロジェクトの時系列

![プロジェクトのガントチャート](../assets/timeline.svg)

<sub>学年を基準にした概略図です。PineNose は開発後もコンテストと改良を継続し、FreqFuseNet は研究完了後に論文投稿へ進みました。</sub>

---

## 01. PineNose

**パイナップルの非破壊熟度・品種判別システム**  
*長庚大学 卒業制作 · チームプロジェクト*

PineNose はガスセンサー、機械学習、画像認識、エッジコンピューティングを組み合わせ、果実を切らずに熟度を推定するシステムです。Arduino でセンサーデータを取得し、Raspberry Pi で熟度を推論します。YOLOv8 と EfficientNet-B0 による画像ベースの品種判別も行い、Web および生産者・消費者向けアプリで結果を確認できます。

私はチームリーダーとして、システム統合、データベースと Docker、センサー・画像認識機能の連携、テストおよび不具合対応に携わりました。

**使用技術：** Python、Arduino、Raspberry Pi、ExtraTrees、YOLOv8、EfficientNet-B0、Flask、Docker

**受賞：** 2026年 農業イノベーション技術コンテスト 金賞

[GitHub リポジトリ](https://github.com/icguproject25-droid/electronic-nose-pineapple-ripeness-assessment)　 ·　 [作品サイト](https://icguproject25-droid.github.io/pinenose_official_site/)　 ·　 [受賞情報](https://ysyct.wda.gov.tw/news_detail.php?id=120)

---

## 02. FreqFuseNet

**頭頸部のリスク臓器を対象とした 3D 医用画像セグメンテーション**  
*Medical Image Segmentation · Research*

FreqFuseNet は、頭頸部の薄壁構造を持つリスク臓器の CT 画像セグメンテーションを対象に、FFT と FcaNet の周波数特徴分岐間に生じるスケール差を検討する研究です。スケール正規化と残差融合によって特徴統合の改善を目指しています。

私はモデル実験、アブレーション分析、ベースライン比較、結果の整理、論文関連作業に参加しました。SegRap2023 データセットを使用しており、medRxiv でプレプリントを公開しています。

**使用技術：** PyTorch、3D CT、Deep Learning、Frequency-domain Features、SegRap2023

[研究コード](https://github.com/Tiffanyxxx3238/freq-spatial-headneck-seg)　 ·　 [medRxiv プレプリント](https://www.medrxiv.org/content/10.64898/2026.07.09.26357642v2)

---

## 03. Academic Portfolio

長庚大学で取り組んだ研究、卒業制作、授業課題をまとめています。マイコン、ハードウェア・ソフトウェア協調設計、コンピュータネットワーク、データ構造、Web 開発、画像処理などを収録しています。

[研究・授業プロジェクト一覧を見る →](https://github.com/lin-jessic/academic-research-portfolio)
