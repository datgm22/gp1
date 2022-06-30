# 2022年度生 ゲームプログラミング入門1
- [シラバス](https://docs.google.com/spreadsheets/d/1lwYMajgOkPfKQsFlrnlZgSKx5OodZL3X/)
- [質問](https://meet.google.com/ips-myqc-jty)
- [Slack](https://datgm22.slack.com)
- [日程](https://github.com/datgm22/gp1/blob/main/thus.md)
- その他
  - [C#書く教科書　記入例](https://github.com/datgm22/csharp-manual)
  - [授業動画](https://github.com/datgm21/gp1/wiki/%E5%BE%A9%E7%BF%92%E7%94%A8%E5%8B%95%E7%94%BB)
  - [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
  - [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)
  - [昨年度の講義資料](https://github.com/datgm21/gp1)

## 参考URL
- [Unity Learning Materials](https://learning.unity3d.jp/)
- [UNITYのインストール手順(準備中)]()
- [Unity入門の森　ゲームの作り方.](https://3dunity.org/game-create-lesson/)
- [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
- [ドットインストール Unity入門](https://dotinstall.com/lessons/basic_unity_v2)
- [Unityスタッフのブックマーク](https://note.com/unityjapan/m/m5978b902c2b5)
- [ハーバード大学 CS50 の日本語版翻訳プロジェクトのページ](https://cs50.jp/)
- [Unityでのモノの動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)
- [テキストファイルの利用](https://docs.google.com/document/d/1Ib6CJYLswOD1y0lAsdagWwtoD0b1Pap4nMtrpdflqV8/)

## 10回目(7/7)

### 予定
- [GP1-13:VisualC# 配列、繰り返し、コントロールをプログラムで追加](https://youtu.be/N8KQp9-whcw?t=583)
  - [前回のプロジェクトv0630](https://github.com/datgm22/v0630)

## 9回目(6/30)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前を`v0630`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を配置
  - ラベル(Label)を2つ
    - label1は`★`、label2は`(・ω・)`を表示
  - タイマー(Timer)を1つ
    - タイマーが動くように設定する
- int型のインスタンス変数`vx`を定義して、-5を代入
- int型のインスタンス変数`vy`を定義して、-10を代入
- timer1の処理で、label1.Leftにvxを、label1.Topにvyを足す
- ラベルがフォームの端で跳ね返るようにする
- label2の位置を、マウスカーソルがlabel2の中央を指すように移動させる
- 以上できたらコミットしてPushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択して、Slackの自分のチャンネルでCtrl + Vキーで貼り付ける

### おまけ問題
- 背景に画像を表示したり、ラベルをPictureBoxに差し替えるなど、思いついたことを改造する
- 以上できたらコミットしてPushする


### 予定
- v0630ができていない人は、[こちら](https://github.com/datgm22/v0630/blob/main/v0630/Form1.cs)を参照して完成させる
- [if文その2](https://youtu.be/1ZgvaXR5Q00?t=578)
- [GP1-12:VisualC# 乱数](https://youtu.be/l3oxBJuWzbE)
- [GP1-13:VisualC# 配列、繰り返し、コントロールをプログラムで追加](https://www.youtube.com/watch?v=N8KQp9-whcw)
- [GP1-14:VisualC# continueとbreak](https://youtu.be/AM1odzCNZcY)
- [GP1-15:VisualC# 定数](https://youtu.be/yMkni9YfS1M)

## 8回目(6/23)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前を`v0623`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を配置
  - ラベル(Label)を1つ
  - タイマー(Timer)を1つ
    - タイマーが動くように設定する
- int型のインスタンス変数`vx`を定義して、-10を代入
- int型のインスタンス変数`vy`を定義して、-10を代入
- timer1の処理で、label1.Leftにvxを、label1.Topにvyを足す
- ラベルがフォームの端で跳ね返るようにする
- ラベルをクリックしたら、MessageBox.Show()で名前を表示したあと、timer1を停止
- 以上できたらコミットしてPushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択して、Slackの自分のチャンネルでCtrl + Vキーで貼り付ける

### おまけ問題
- ラベルをもう一つ配置して、`Score 0`と表示
- int型のインスタンス変数`score`を定義して、100を代入
- timer1の処理に以下を追加
  - scoreを1減らす
  - 追加したラベルに、`Score `に続けて変数`score`の値を表示
- 以上できたらコミットしてPushする

### 予定
- [GP1-08:if文 / switch文](https://youtu.be/fDBRR3xg_Tk?t=1308)の続きから
  - fukuvHensu を開く
- [GP1-10:VisualC# マウス入力](https://youtu.be/bUaPhQxuO8M)
- [GP1-11:VisualC# if文その2](https://youtu.be/1ZgvaXR5Q00)
- [GP1-12:VisualC# 乱数](https://youtu.be/l3oxBJuWzbE)

## 時間があれば
- [GP1-04:Unity ボタン](https://youtu.be/aP56UZ953Hg)



## 7回目(6/16)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前を`fukuvHensu`にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を配置
  - ラベル(Label)を1つ
  - テキストボックス(TextBox)を2つ置く
    - どちらのTextも`0`を設定
    - どちらも非表示にする
  - ボタンを4つ置いて、十字に配置
  - タイマー(Timer)を1つ
    - タイマーが動くように設定する
- タイマーに以下のプログラムを書く
  - 一方のテキストボックスの値をint型に変換して、ラベルのLeftに足す
  - もう一方のテキストボックスの値をint型に変換して、ラベルのTopに足す
- ボタンを押すと、それぞれの場所に合わせてラベルが移動方向を変えるようにする
- ラベルをクリックしたら自分の名前をMessageBoxで表示
- できたらコミットしてPushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択して、Slackの自分のチャンネルでCtrl + Vキーで貼り付ける

#### ボーナス問題
上記ができた人向けのボーナス課題。

- `int`型の変数`vx`と`vy`を定義して、どちらも`0`を代入
- ボタンを押した時に値を設定する先を、テキストボックスから`vx`と`vy`に変更する
- タイマーの処理で使用していたテキストボックスを`vx`と`vy`に変更する
- テキストボックスを削除する
- ラベルをクリックしたらタイマーを止める
- その他、思いついたことを実装
- できたらコミットしてPushする

### 内容
- Unityの`u0609`を開いて前回の振り返り
- 復習問題
- [変数(2)](https://youtu.be/smKALzN0Gus?t=1810)の続きから
- [GP1-08:if文 / switch文](https://youtu.be/fDBRR3xg_Tk)
  - fukuvHensu からそのまま継続


## 6回目(6/9)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前をfukuv0609にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- フォームに以下を設置
  - ラベル(Label)を1つ
  - テキストボックス(TextBox)を2つ置いて、どちらのTextも1を設定
  - タイマー(Timer)を1つ
- ラベルをクリックすると、MessageBoxで自分の名前を表示
- タイマーに以下のプログラムを書く
  - 一方のテキストボックスの値をint型に変換して、ラベルのLeftに足す
  - もう一方のテキストボックスの値をint型に変換して、ラベルのTopに足す
- タイマーが動くように設定する
- できたらコミットして、Pushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択して、Slackの自分のチャンネルでCtrl + Vキーで貼り付ける

#### 上記ができた人向けのボーナス課題
- ボタンを4つ、十字に配置して、ボタンを押したらその方向にラベルの移動方向が変わるようにする
- 方向ごとにラベルの表示を変更する
- ラベルをクリックしたら、名前が表示された後に、タイマーを停止させる

### 内容
- 07.md 変数～動的なプログラム～ からをUnityで
  - [GP1-07 変数](https://youtu.be/z8KlJWFuskc)
  - [GP1-07 変数(2)](https://youtu.be/smKALzN0Gus)


## 5回目(6/2)

### 話題
- [ハーバード大学 CS50 の日本語版翻訳プロジェクトのページ](https://cs50.jp/)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前をfukuv0602にする
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- 以下のものを作る
  - ラベル(Label)を1つ
  - ボタン(Button)を4つ作って十字に配置
  - ボタンを押した方向にラベルが動くようにする
- ラベルをクリックすると、MessageBoxで名前を表示
- できたらコミットして、Pushする
- さらに、プログラムコードのスクリーンショットをSlackの自分のチャンネルに貼り付ける
  - スクリーンショット：　ウィンドウズキー + Shift + S キーを押して、スクリーンショットを取りたい範囲をマウスでドラッグで選択して、Slackの自分のチャンネルでCtrl + Vキーで貼り付ける
![image](https://github.com/datgm21/gp1/blob/main/image.png?raw=true)

### おまけ
上記ができて時間が余った人は、以下にも取り組んでみよう。成果物はGitHubでPushすれば更新されるので、改めて報告は不要。

- 動く方向に応じて、ラベルの表示を変化させる
- 動くごとにラベルの表示を変える
- ラベルをクリックして、名前を表示した後に、ラベルを消す
- その他、思いついたことを試す

### 内容
- [GP1-06:VisualC# コントロール(Control)～表現を増やす～](https://youtu.be/MAie5pHmFyg)

### 時間があれば
- [GP1-06:Unity 移動](https://youtu.be/hnsH9L5ZBD8)
  - [Unityでのモノの動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)


## 4回目(5/19)

### 話題
- [Christoph Molnar. 説明可能なAI](https://hacarus.github.io/interpretable-ml-book-ja/)

### 復習問題
- Visual C#の新規プロジェクトを作成して、名前を`fukuv0519`にする
- GitHubにPublishする
- ボタンを3つ配置する
- 1つ目のボタンに「氏名」と表示する。そのボタンをクリックすると、そのボタンの表示が自分の名前に変わるようにする
- 2つ目のボタンに「消える」と表示する。そのボタンをクリックすると、そのボタンが消えるようにする
- 3つ目のボタンに「上」と表示して、フォームの中央辺りに配置する。そのボタンをクリックすると、そのボタンがフォームの上端に移動するようにする
- プロジェクトの更新をGitHubに反映させる
- 作成したGitHubのリポジトリーのURLを[こちら](https://docs.google.com/forms/d/e/1FAIpQLSdPXGSQ3ueVghzfhK7DAGMT4nFAj9RK3wM842cuz9i_LPFzUA/viewform?usp=sf_lin)に報告する

#### おまけ
上記ができて時間が余った人は、以下のようなことにも取り組んでみよう。成果物は、GitHubでPushすれば更新されるので、改めて報告は不要。

- 新しいボタンを作って、クリックすると色が変わるようにする
- ラベルを作って、クリックすると表示が変わるようにする


### 内容
- [GP1-05:VisualC# データの型、計算](https://youtu.be/Gum71fCVsb4)


## 3回目(5/12)

### 準備
- GitHubを開く > Sign in > csharp-manual を開く
- 03.mdをクリックして開く

### 復習
- Visual C#の新規プロジェクトを`fukuv0512`という名前で作成する
- ボタンを3つ置く
- ボタンに表示されている文字を、1つ目のボタンを`氏名`, 2つ目のボタンを`PCの番号`, 3つ目のボタンを`自宅のPC環境`に変更する
- 1つ目のボタンを押したら、自分の氏名を表示
- 2つ目のボタンを押したら、モニターのシールに`A601-00`というように書かれている文字列を表示
- 3つ目のボタンを押したら、自宅にWindowsPCがあれば`Windows`、macなら`mac`、両方あれば`両方`、持っていないなら`なし`と表示

以上実装が完了したら実行して、それぞれのボタンを押してメッセージが表示されている画面をスクリーンショットで撮影して、Slackの自分のチャンネルに貼り付けよ。

スクリーンショットの撮り方

- Windowsキー + Shiftキー + Sキー を押す
- コピーしたい画面の範囲をドラッグして選択
- Slackの自分のチャンネルのコメント欄を選んで、Ctrl + Vキーで貼り付け

### 内容
- `v0512`という名前で新しいプロジェクトを作成
- [VisualStudioのプロジェクトをGitHubにPublishする](https://github.com/datgm21/gp1/wiki/VisualStudio%E3%81%AE%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92GitHub%E3%81%ABPublish%E3%81%99%E3%82%8B)
- [手順動画 Visual C#](https://youtu.be/BVRWsai9NOw)
- [プロジェクトの更新をGitHubに反映させる](https://github.com/datgm21/gp1/wiki/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E6%9B%B4%E6%96%B0%E3%82%92GitHub%E3%81%AB%E5%8F%8D%E6%98%A0%E3%81%95%E3%81%9B%E3%82%8B)


## 2回目(4/28)

### 内容
- [手順動画](https://youtu.be/lTNRVO3PPhE)
- [書く教科書のオリジナルリポジトリー](https://github.com/tanakaedu/csharp-manual) を右クリックして、新しいタブで開く
- 右上の Fork ボタンをクリック
  - Fork(フォーク)とは
    - GitHubのリポジトリーを、自分のリポジトリーにコピーする作業のこと
    - 参考：GitHubは、オープンソースプロジェクトの開発が主目的のサービスです。
    開発者が公開しているオープンソースのリポジトリーをコピーすることで、元のプロジェクトと切り離して自由に改変することができます。
    手元で開発をして有効な改良ができたら、Pull Request(プルリクエスト=組み込むことを要求)で改良内容を元のプロジェクトに送信します。
    プルリクエストが届いたら、開発元の人は要求内容をチェックして、問題がなければプロジェクトに取り込むことができます。
    この流れで、世界中の各地で、同時に、一つのプロジェクトの開発が行われています。

以上で、自分のGitHub上に書く教科書がコピーされました。必要な項目を自分で書き加えていき、完成させてください。

### Slack準備
- [Slackに参加]()
- チャンネルを追加する を押して、`times_名前` を入力して作成する。説明とプライベート設定は不要
- 作成した自分用のチャンネルを選択


### 演習
講義で自分で作成した教科書を参考にして、以下のプログラムを作成してください。

- プロジェクト名を ensyu0428 とする
- ボタンを１つ配置して、ボタンのテキストを`自己紹介`にする
- 自己紹介 ボタンを押したら、自分の名前を`MessageBox`で表示する
- 以上できたら、実行画面のスクリーンショットを撮って、Slackの自分の活動チャンネル(#times_名前)にCtrl+Vで貼り付ける
  - 作成したプログラムを実行して、ボタンを押して、メッセージボックスを表示しておく
  - ウィンドウズキー+Shift+Sキーを押したら、スクリーンショットを取りたい範囲をマウスでドラッグで選択
  - Slackの自分のチャンネルのコメントのところをクリックして選択したら、Ctrl+Vキーでスクリーンショットを貼り付ける
  - 右下の送信ボタンでメッセージを送信する



### GW中の自習
- e-typing
- [UNITYの準備](https://am1.jp/unity/getting-started/)
- [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
  - アカウントをGitHubで登録
- [Unity Learning Materials](https://learning.unity3d.jp/)
- [ドットインストール Unity入門](https://dotinstall.com/search?q=unity&f=topbar)


## 1回目
- [使用NGのPC](https://docs.google.com/spreadsheets/d/1-PDzfdsGWkt1O06c1C_27_GPiXijEbbRYSGz0RmlJOI/)
  - 赤いPCの人は、19番以降の席へ移動してください
- この講義のURLは https://github.com/datgm22/gp1
  - [GmailアカウントとGitHubアカウントを作成していない場合はこちら](https://docs.google.com/document/d/16MW6maMYvt8m-60RM5wU_LzJ5r-3Hm0WTnxoBGDzxIA/)
- ガイダンス
  - [プログラミングを学ぶ前に](https://docs.google.com/presentation/d/1mIIrnua1nf2yCiXA6KMkTUOylzPIxiUCeqQEdtHdPhc/)
  - [講義メモ](https://docs.google.com/document/d/1u5hTFDD96oNmaKXQHED5knrz0io9p51hMSqNAuIhyR8/)
    - Visual C# / Unity
  - 独習
    - [Unity Learning Materials](https://learning.unity3d.jp/)
    - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
      - アカウントをGitHubで登録
    - [ドットインストール Unity入門](https://dotinstall.com/lessons/basic_unity_v2)
    - この1年でUnity関連の良質な記事が増えたのでよいページを探してみてください！

