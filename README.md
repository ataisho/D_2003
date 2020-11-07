# All Seeing Eyes
[![IMAGE ALT TEXT HERE](https://jphacks.com/wp-content/uploads/2020/09/JPHACKS2020_ogp.jpg)](https://www.youtube.com/watch?v=G5rULR53uMk)
## 製品概要
Office ✖️ Tech
### 背景(製品開発のきっかけ、課題等）
現在，COVID-19が世界中で猛威を振るっています．COVID-19が与えた損害，そして今後も与える損害は計り知れません．
しかし，私たちはいつもの感覚で，マスクを付けずについつい人と近距離で話してしまうことも...．
そこで，私たちはこの問題を解決するため，人の密を自動検出して警告してくれるシステム「All Seeing Eyes（ASE）」を開発しました．
私たちの作品「ASE」が何気なく生じる密を防ぐことで，安心できる快適なオフィス環境をあなたに提供します．

### 製品説明（具体的な製品の説明）
All Seeing Eyes（ASE）は，「マスクの着脱」や「近距離での会話」のような何気ない密を防ぐシステムです．

あなたがマスクを着用しているかを検知し，人との距離を計測し，ソーシャルディスタンスが保てていない空間に対しては密を通知します．

通知方法はスマートスピーカーによる音声通知，画面での画像通知の2つがあります．

また，密が検出された時間の記録も行ない，密の再発防止に繋げることが可能です．

ASEを使用して安心できる快適なオフィス空間を作りませんか．

### 特長
1. 人の密を検知

カメラとLiDARを併用することで，奥行きも考慮した正確な人同士の距離を検出可能です．
2. マスクの着脱を検知

密を人の距離だけでなく，マスクを着脱を判断基準に追加することで，オフィスへの出勤が徐々に再開している現代社会に合った密検出システムを実装しています．
3. 音声，動画，テキストの様々な形で密を通知

密になっている当人に対する音声通知と，オフィスとして密が起こりやすい場所や時間を把握したい人に対する動画通知・テキスト通知の2方向の通知を行なうことで，オフィス全体で密の防止に勤めることが可能です．

### 解決出来ること
何気なく生じる密を防ぐことで，安心できる快適なオフィス環境を提供できる

### 今後の展望
* ログデータより密になりやすい時間帯などを解析することで密の再発防止に繋ぐ
* 通知方法や表示カメラ映像の選択，密の検出基準（例：マスクを着けていても近づいたら密と判断）の選択などをGUIから簡単に実施できるようにする
* 3密（密閉・密集・密接）の分類を行なう

### 注力したこと（こだわり等）
**YOLOとLiDARの情報を統合**
人と人の距離を正確に検出するため，カメラとLiDARの情報を統合した奥行きを考慮した位置マッピングを実装
**音声，動画，テキストで密を通知**
状況に合わせた通知方法の選択が可能
**機械学習を利用したマスクの着脱検出を実装**
物体検出手法であるYOLOを画像データセットで学習させ，マスクの着脱を正確に検出可能

## 開発技術
### 活用した技術
#### API・データ
* IFTTT
* Node.js
* nginX
#### フレームワーク・ライブラリ・モジュール
* PyTorch(YOLO)
#### デバイス
* LiDAR
* Raspberry Pi
* Google Home
* Webカメラ
### 独自技術
#### ハッカソンで開発した独自機能・技術
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください。
#### 製品に取り入れた研究内容（データ・ソフトウェアなど）（※アカデミック部門の場合のみ提出必須）
* 
*
