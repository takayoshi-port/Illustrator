# Illustrator
イラストを投稿し、評価することができる自作webサービスです。
![スクリーンショット-2019-12-11-22 48 23](https://user-images.githubusercontent.com/48384384/71505061-34ec7e00-28bf-11ea-9dac-12ed6f175bff.png)
<br>

# Dependency
HTML、CSS、javascript(jQuery、ajax)、PHP(Version 7.3.7)、MySQL

# Setup
MAMPを導入し、ローカル環境にて各ファイルをhtdocsファイルに配置。(MacOS)
DBにはMySQLを使用。

# Usage  
主な機能
###### 新規会員登録機能
###### プロフィール情報変更機能
###### パスワード変更機能
###### パスワードリマインダー機能
###### ログアウト機能
###### イラスト投稿機能
###### イラスト詳細画面
###### ブックマーク機能
###### 検索機能
###### 退会機能

### ・新規会員登録機能

![1 新規会員登録](https://user-images.githubusercontent.com/48384384/71536929-767d3780-2958-11ea-8542-02eac5b50476.gif)

名前、email、パスワード、パスワードの再入力欄を入力し、DBに登録します。

バリデーションチェック項目
・各項目の未入力項目  
・名前の最大文字数(20文字)  
・emailの最大文字数(255文字)  
・DBに登録されているemailの重複  
・パスワードが半角英数字か  
・パスワードの最大文字数(255文字)  
・パスワードの最小文字数(6文字)  
・パスワード再入力の最大文字数(255文字)  
・パスワード再入力の最小文字数(6文字)  
・パスワードとパスワード再入力が同値か  

### ・プロフィール情報変更機能

![2 プロフィール変更](https://user-images.githubusercontent.com/48384384/71536931-7b41eb80-2958-11ea-8005-03cb717ee07d.gif)

DBに登録されているプロフィール情報を変更します。

バリデーションチェック項目  
・名前の最大文字数(20文字)  
・居住地の最大文字数(255文字)  
・職業の最大文字数(255文字)  
・emailの最大文字数(255文字)  
・DBに登録されているemailの重複
・Emailの形式
・Emailの未入力
・コメントの最大文字数(255文字)  

登録後のプロフィール情報は作品ページの作者情報から閲覧可能です。

![5 5 プロフィール](https://user-images.githubusercontent.com/48384384/71536942-8b59cb00-2958-11ea-86a6-14a1cd56b048.gif)

### ・パスワード変更機能

![3 パスワード変更](https://user-images.githubusercontent.com/48384384/71536933-7ed57280-2958-11ea-914b-7ed618631229.gif)

DBに登録されているパスワード情報を変更します。

バリデーションチェック項目

・パスワードが半角英数字か  
・パスワードの最大文字数(255文字)  
・パスワードの最小文字数(6文字)  
・パスワード再入力の最大文字数(255文字)  
・パスワード再入力の最小文字数(6文字)  
・パスワードとパスワード再入力が同値か  

### ・パスワードリマインダー機能

![3 5 パスワードリマインダー](https://user-images.githubusercontent.com/48384384/71551470-e90b1780-2a2b-11ea-80dc-c5ba45c425cd.gif)

DBに登録されているメールアドレスを入力することでパスワードを再登録できる機能です。

### ・ログアウト機能

![4 パス変更後ログアウト](https://user-images.githubusercontent.com/48384384/71536941-8b59cb00-2958-11ea-97b1-99c6b256b2d0.gif)

現在ログインしているアカウントをログアウトします。

### ・イラスト投稿機能

![5 イラスト投稿](https://user-images.githubusercontent.com/48384384/71536943-8bf26180-2958-11ea-8c9b-69036d627f4f.gif)

イラストを投稿する機能です。
投稿したイラストはマイページに追加されます。

バリデーションチェック項目

・タイトルの未入力チェック
・タイトルの最大文字数(255文字)  
・タイトルの最小文字数(6文字)  
・投稿画像の有無  

### ・イラスト詳細画面

![6 イラスト詳細](https://user-images.githubusercontent.com/48384384/71536945-8bf26180-2958-11ea-889c-27ddb2e97720.gif)
![7 イラストコメント](https://user-images.githubusercontent.com/48384384/71536946-8bf26180-2958-11ea-893a-d01c4ff7bbf8.gif)

投稿されたイラスト情報を表示します。  
ページ下部にあるコメント欄からイラストに対するコメントを投稿することができます。

### ・ブックマーク機能

![8 ブックマークとページング](https://user-images.githubusercontent.com/48384384/71536947-8c8af800-2958-11ea-9e6c-636149462f38.gif)
![9 ブックマークとページング２](https://user-images.githubusercontent.com/48384384/71536948-8c8af800-2958-11ea-9a03-51a282395d12.gif)

桜花したイラスト詳細画面にてブックマークボタンを押下した場合、  
マイページでブックマークしたイラストを閲覧することができます。

### ・検索機能

![9 1 検索機能](https://user-images.githubusercontent.com/48384384/71553789-b4618500-2a58-11ea-936f-57bdd2d30eb1.gif)

イラスト検索欄に文字を入力して検索することで、  
検索ワードがタイトルに含まれるイラストを表示します。

### ・退会機能

![10 退会](https://user-images.githubusercontent.com/48384384/71536949-8c8af800-2958-11ea-9877-0453844ee270.gif)

アカウント情報を削除します。



# Authors
Takayoshi
