# 2022年度生 ゲームプログラミング入門1
- [シラバス](https://docs.google.com/spreadsheets/d/1lwYMajgOkPfKQsFlrnlZgSKx5OodZL3X/)
- [質問](https://meet.google.com/ips-myqc-jty)
- [Slack](https://datgm22.slack.com)
  - [これを開いて登録](https://join.slack.com/t/datgm22/shared_invite/zt-17esv8n6a-TICdE~7YwN~rJN76QM_GpQ)
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

## 3回目(5/12)

## 準備
- GitHubを開く > Sign in > csharp-manual を開く
- 03.mdをクリックして開く

## 内容
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

