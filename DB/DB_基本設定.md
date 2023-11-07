# データベース
## 事前準備
### H2 データベース作成
- 画面右側の「データベース」を押す

- 新規作成「+」を押す

- データソース　→　H2を選択する

![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-25%20152607.png)

- ドライバータブに移動し、H2を選択する

- H2のバージョンを1.4.200にし、データソースのH2に戻る

![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-25%20152852.png)

- 以下の通りに設定する

    - 名前：db_prac

    - コメント：db学習

    - 接続タイプ：Embedded

    - パス：~/h2db/db_prac;Mode=PostgreSQL;AUTO_SERVER=TRUE;

    - ユーザー、パスワード：各自の学籍番号

設定後、「接続のテスト」を押し、成功と出るのを確認してください。確認できたら「OK」を押し、次に進んでください。

![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-25%20153125.png)


[演習](../Lecture/lecture4.md)にもどる
