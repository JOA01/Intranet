<h1># Project No.1 </h1>
<h2>1. Project Name: 社内イントラネット</h2>


<h2>2. 開発目的とプロジェクト概要</h2>

 1) 開発目的 : <br>
 無限商事という仮想の会社が使う社内イントラネットを実現しました。<br>
 社員DB情報に基づいて人事部に属した職員は、会社にお知らせを管理したり、<br>
 管理者モードを利用できるようにアクセス権限を与えました。<br>
 2) 開発人員 : 4人<br>
 3) 開発期間 : 2019.11.27 ~ 2019.12.06 (8日間) <br>


<h2>3. 開発環境</h2>
 1) 言語 : JAVA, JAVA Swing, SQL<br>
 2) OS : Windows 10 Home<br>
 3) DB : Oracle Database 11g Express Edition<br>
 4) Tool : Eclipse, SQLDevelopter, Netbeans<br>
 
 
 <h2>4. UIストーリーボードと核心技術</h2>
  1) UIストーリーボード<br>
<img src = "https://user-images.githubusercontent.com/50767972/85540968-88fbd380-b652-11ea-9d81-b27ae6ab1320.PNG" width = "90%"></img>    
  2) 核心技術<br>
     JFrame UIを実現<br>
     データベース設計<br>
     JDBCを利用したDatabase連動<br>

<h2>5. データベースの構造</h2>
<img src = "https://user-images.githubusercontent.com/50767972/85547765-2ce87d80-b659-11ea-81b5-51a651d54173.PNG" width = "90%"></img>
<img src = "https://user-images.githubusercontent.com/50767972/85542740-594dcb00-b654-11ea-9609-62da0d2ac9e9.PNG" width = "90%"></img>


<h2>6. スクリーンショット</h2>
<h4>1) ログインの画面</h4>
- 既存登録社員のみ入場可能となっています。 ＩＤ（社番）や暗証番号を入力せずにログインを押すと、警告ウィンドウが表示されます。ＩＤ（社番）や暗証番号が一致しない場合、警告のメッセージが表示されます。 登録されたID(社番)でない場合、警告のメッセージが表示されます。 ID(社番)とパスワードが一致した場合、ログインボタンを押すとお知らせ画面に移動します。<br>
<img src = "https://user-images.githubusercontent.com/50767972/85543739-4c7da700-b655-11ea-8564-4e72aa009b2a.PNG" width = "90%"></img>
<br>
<h4>2) 公知事項の画面</h4>
<img src = "https://user-images.githubusercontent.com/50767972/85543851-67e8b200-b655-11ea-993b-939217b1873d.PNG" width = "90%"></img>
<br>
<h4>3) 簡単な掲示板の画面</h4>
<img src = "https://user-images.githubusercontent.com/50767972/85543920-7931be80-b655-11ea-8ba7-775834e9fc7f.PNG" width = "90%"></img>
<br>
<h4>4) 管理者モードの画面</h4>
<img src = "https://user-images.githubusercontent.com/50767972/85544019-8fd81580-b655-11ea-8da7-f6a852f8a14d.PNG" width = "90%"></img>
<br>
<h4>5) メッセージの画面</h4>
<img src = "https://user-images.githubusercontent.com/50767972/85544077-9feff500-b655-11ea-84e3-140634be3c9d.PNG" width = "50%"></img>
