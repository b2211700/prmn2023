# git

## はじめに

- 分からないときはすぐに担当のb3に聞く
  - 分からないことは次に持ち越さないこと
- 予習/復習は必ず行うこと
  - 前回までの知識は全て習得しているものとして進行します
- **課題はGithub上にpushすること**
  - Githubの使い方を学びます
  - 課題の質問をするときなどにGithub上にあげておくと確認しやすいです
- 時間外の質問/相談はDiscordまたはZoomで  
  - Zoomで聞いた方がいいこともあります
- 解答は確認程度に
  - 課題の解答がありますが、あくまで参考程度としコピペは極力しない
- 連絡はこまめに
  - 既読通知機能がDiscordにはないので...
  - Discordで質問等するときはメンターをメンションして聞いてください

### Githubの準備
以下はGithubアカウントがあることを想定して進めます
- Windowsの人は[GitBashのダウンロード](https://gitforwindows.org/)
Macの人はターミナルで git config でユーザ登録を行なっていない人は以下のコマンドから登録する
```
$ cd
$ git config --global user.name [GitHubに登録したユーザ名]
$ git config --global user.email [GitHubに登録したメールアドレス]
```
現在の登録を確認するコマンド
```
$ git config --global --list
```

- [Github](https://github.co.jp/)にアクセスし、サインインする
- Github上にリモートリポジトリを作成する
  - 以下のボタンをクリック
  	![image](https://i.imgur.com/nF6O0bi.jpg)

  - 以下のように入力し、Create Repositoryをクリックする。ここまででリモートリポジトリは完成
```

Githubのリポジトリを更新して、プロジェクトがpush出来ていたらOK

GitBashやターミナルでも同じコマンドでpushを行えるが、--ディレクトリをプロジェクトまで移動するのを忘れないように--
pushはできるだけ細かく行い、コメント文は簡潔に([パッケージ](https://github.com/fujiitomoko/ProjectMember2022Document/edit/main/Lecture/Lecture1.md#パッケージ)・[クラス](https://github.com/fujiitomoko/ProjectMember2022Document/edit/main/Lecture/Lecture1.md#クラス)・[メソッド](https://github.com/fujiitomoko/ProjectMember2022Document/edit/main/Lecture/Lecture1.md#メソッド)を作ったときなど)
```


### クラスの作成

- 左側のメニューのsrc > lecture01を 右クリックする
- New > Java Class を選択する
- Nameには "Main" と記入しOKを押す

今後クラス作成をするときは、各lectureXXパッケージ内に作成すること

![image](https://user-images.githubusercontent.com/85465441/197342085-f66a8e15-0e1c-4740-9587-8f7ab9c17a33.png)

## 何もしないプログラム

- Mainクラスの {} の中にカーソルを合わせる
- `psvm` とタイプしTabキーを押す
  - 生成されたコード部分
  ```
  public static void main (String[] args){
	  //本来ならここに処理を書く
	  //スラッシュを2つ打つと、コメント文として認識される。
	  //コードの可読性の向上につながるので、書く癖をつけよう
	  //行を選択して「ctrl+/ (command+/)」で選択行をコメント文に変更できる(複数行可)
  }
  ```
  をmainメソッドと呼ぶ。

- コード入力スペース上で右クリックをする
- Run ‘Main.main()’ をクリック

画面下部に `Process finished with exit code 0` と表示されることを確認する


## gitの操作方法
- 以下のリンクからgitの操作について学習してください。

[gitの操作方法 基本編](https://freezing-botany-749.notion.site/git-78e71b8b562343d885b6d1e158ffa9a0?pvs=4)


[gitの操作方法 練習編(ローカルリポジトリ)](https://freezing-botany-749.notion.site/1-d969a1a418aa49eca786dde3d2c29750?pvs=4)


[gitの操作方法 練習編(リモートリポジトリ)](https://freezing-botany-749.notion.site/2-d99d2adda60d499eafc644d589515d74?pvs=4)



gitのパートはここまでになります。お疲れさまでした！

[目次へ](../README.md)
