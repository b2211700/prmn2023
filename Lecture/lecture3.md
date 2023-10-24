# データベース
## 事前準備
### プロジェクトの作成
- IntelliJ IDEAを起動し、ファイル　→　新規　→　プロジェクトを選択する
  
  

![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-16%20131056.png)
  
 

- 以下の画面になったら、「Spring Initializer」を選択し、


    - 名前：prmn2023


    - 言語：Java


    - 型：Maven


    - JDK：temurin-17


    - version：17


と設定し、「次へ」を押す
  
  
 
![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-16%20134331.png)
  
  
  
  
- 以下の画面になったら、「SQL」を選択し、


    - JDBC API


    - H2 DataBase


にチェックを入れ、「作成」を押す
  
  
 
  
![image](https://github.com/Shodaiki/2022prmna/blob/main/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202023-10-16%20134825.png)



### H2 データベース作成
- 画面右側の「データベース」を押す

- 新規作成「+」を押す

- データソース　→　H2を選択する

- ドライバータブに移動し、H2を選択する

- H2のバージョンを1.4.200にし、データソースのH2に戻る

- 以下の通りに設定する

    - 名前：db_prac

    - コメント：db学習

    - 接続タイプ：Embedded

    - パス：~/h2db/db_prac;Mode=PostgreSQL;AUTO_SERVER=TRUE;

    - ユーザー、パスワード：各自の学籍番号

設定後、「接続のテスト」を押し、成功と出るのを確認してください。確認できたら「OK」を押し、次に進んでください。


今回はここまでになります。お疲れさまでした。

[目次へ](../README.md)

