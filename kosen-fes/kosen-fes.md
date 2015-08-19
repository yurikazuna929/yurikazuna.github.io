# 2015年度 3e高専祭プロジェクト
* 更新履歴
* はじめに
* ウォーリーをさがせ！
* 自作「かみなり」
* ゲームを作ろう！
* 事務的な話

## 更新履歴
8/12:文書を作成しました。

## はじめに
* 文責：ゆーり(e1333)
* しれーかん：ゆーり(e1333)
* 生け贄：くもは(e1329),タッツー(e1306),クック(e1307),つよし(e1322)

高専祭は10/31(土)と11/1(日)です。
計画的に準備して爽やかに当日を迎えましょう。

当日までのスケジュールは[コチラ](kosen-fes.pdf)にまとめてあります。
黄色背景が班員に、桃色背景がみんなに協力してもらう事案となります。

### 運営からのひとこと
ゲーム作るのほんとに興味無いですか・・・。
ほんとに初心者の初心者でも大丈夫なんですって。手取り足取り教えるので・・・。
Processingほんとに簡単なので・・・。

### お読みください(4件)
* 例年、全員に当番制を敷いて作業にあたってもらっていましたが、作業の進捗が思ったよりも出ないことが明らかとなってしまっているので、今年は当番制はなしにします。夏休みの作業もありません。
* 生け贄を何人か作っていますが、これは全員でやらなくても良いことをやるための人員です。決してみなさんがやるべき仕事を肩代わりしてくれる人ではありません。
言い換えると、「皆さんには最小限しかお願いしないので、それだけは協力して。」
* 高専祭関連についての質問等はゆーり(yuri.kazuna@gmail.com)にお願いします。
基本的に1日以内に返事をします(「確認しました。」のみであっても)。
返事がない場合はなにかが起こっているので、代わりに、
くもは(e1329@s.akashi.ac.jp)か、
文化委員(e1325@s.akashi.ac.jp||e1334@s.akashi.ac.jp)にお願いします。
* 周知事項、重大な変更・決定などはクラスのメーリングリストとLINEを使って連絡します。
また、Chatworkは公開議論所なので、議論案件が出た時に使います。

* * * *

* * * *

## ウォーリーをさがせ！
### 概要
QRコード付きのTシャツを着たクラスメンバーを学校中に配置する。
お客さんはそれらを見つけてQRコードを撮影。
QRコードにはそれぞれ別のURLが割り当てられており、
URLのジャンプ先でCookieなどを入手し、見つけた人の情報を記憶させる。
各日、数人の「ウォーリー」を決めておき、それらの情報を持ってきた人には、
3e教室にて褒美を与える。

### 工程
* 概要を決める
* Tシャツのデザインを決める

* * * *

* 割り当てるURLを決める
    + 使うサーバを決める
    + 動的QRコードを使うかを決める
* 業者tmixにTシャツを発注する(9/22)
    + 必ずQRコードが読み取り可能な解像度で印刷できるかを確認する
    + 都市科のTシャツ発注状況と照らしあわせて、最終的な要求金額を全員に公示する
* Webページを用意する
    + 各人のフリースペースとするか、決められたページにするかを決める
    + 実装方法を決める(Python使うかとか)
* QRコードの読み取り方法を確認する
    + OS(Android2.3,ガラケー,タブレットなども含む)ごとの読み取り方法を調べる。
* 指名手配書を作成する
    + 実行委員会に張り紙の許可を取る
    + 教室に掲示する情報を決める
* クラスメンバーの動きを確認する(10/25)
    + 具体的な配置は指定しない予定(引きこもるな等の指示のみ)
    + 教室担当のメンバーの動きを確認する
    + 褒美を決める(Additional)
     + 電子工作の素子でアクセサリを作るのがよさげ(来年売りたい)
* 高専祭を成功させ、勝利の美酒に酔いしれる(成人のみ)
* 集金する
    + 集金まではゆーりが全額立て替えておきます
    + 集金額はゆーりが直接お伝えするので、伝えられたら速やかに

### 注意事項
* 発注前に見積もりをしなければならない。8月中に開始すること。
* Webページを用意する時に全員の協力が必要になるので、早めにやること。
* Webページに関する議論は早くにやっておいて、作りこむ時間を与えることも可能である。

* * * *

* * * *

## 自作「かみなり」
### 概要
教室にて、放電に関する展示を行う(要検討)。
なお、インパクトよりも安全性、迫力よりも安心感を重視する。
また、「かみなり」の設計書や、手順書などはレポートの形にして展示しておく。
これには、高専を夢見る中学生にナマのレポートを見せることによって、
中学生の将来を守る目的があり、非常に重要である。(平易なものも作る)

### 工程

* * * *

* 概要を決める
    + どのような放電を取り扱うかを決める
    + 機材の使用を教員に相談する
* 設計する(9/9)
    + 自作する部分としない部分を考える
    + 作業期間は10/1*10/14の2週間と仮定して、その中で実現可能な量にする。
    + ただし、実際の作業はもっと早くて良い
* 部品を発注する
    + 「ウォーリーをさがせ！」の褒美のパーツを同時に発注する
    + 領収書を切る
* レポートを作成する(9/30)
    + 理論値などを出して中学生が実際に実験できるようにするとなお良い
* 実装する(10/14)
* 10回実験する
    + 部品の劣化・消耗の目安を掴んでおく
    + 消耗品の追加発注も必要ならしておく
    + 必ずあらゆる危険性を確認しておく(回路に手を触れるなど)
* 高専祭を成功させ、片付けの際に教室のドアで静電気に痛い思いをする

### 注意事項
* 電気は常に命の危険が伴うので、危険な展示を行わないことはもちろん、
作業する際は深夜を避けて作業する(事故防止・事故しても病院が開いている)こと。
* 生け贄が生じる展示なので、スケジュールを確実に守ること。
各工程を先送りにするとろくな事にならないので早めを意識する。
* 最も実装する展示なので、例年のノリだと必ず失敗することを留意しておくこと。
* 疑問が生じたらすぐに教員に相談し、フェイルセーフを意識しておくこと。

* * * *

* * * *

## ゲームを作ろう！
### 概要
何も楽しいことを教えてくれない学校の情報教育に代わって、楽しくゲームを作って情報系の楽しさを再認識しよう！
ゲーム創作研究部もゲームを展示していますが、今年は場所が大きく離れているし、
なにより、展示するゲームの種類は全く別(こちらのほうがはるかにクオリティが下)なので競合しません。
予算を割くつもりはないので、「Processing」を使ってキーボードだけで軽く遊べるゲームを1ヶ月程度で作っちゃいましょう。
初心者歓迎です！

### 工程
* 生け贄を見つける

* * * *

* ゲームを作成する(9/30)
    + 質問事項は10分調べてわからなければゆーりまで
    + どのようなゲームを作るにせよ、操作は簡単に、ルールは単純に
 目安は中学生の母親でも1回やればルールがわかって遊べるくらい
    + リソースは要相談
* テストプレイをして、バグを見つけたり、わかりにくいところを潰す
    + ゲームはテストプレイが命
 新学期入ったら制作を終了してテストプレイフェイズに入るのが理想
* 高専祭を成功させ、みんなで情報工学コースを選択する

### 注意事項
* 色を扱うゲームは色覚異常の人がいることに注意しておくこと。
そうでなくても明度差をつけたりして、画面の角度によって色の認識がおかしくならないようにする。
* 難しいことを考えないこと。
より良い設計、オブジェクト指向、計算量・・・
そんなことを考えるとゲームが作れなくなります。
クズみたいなコードを書きましょう。
* でも名前付けに妥協しないこと。
詳細は参加者に伝えます。

* * * *

* * * *

## 事務的な話
上記以外の、高専祭に必要な話

### 教室のレイアウト
予定では

* 「ウォーリーをさがせ！」のご褒美カウンター
* 放電実験室
* ゲームコーナー

を教室内に作る予定です。
領域・人員を検討しましょう(未検討)。(10/14)
