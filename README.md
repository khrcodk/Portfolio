# Portfolio
このページは私の個人プロジェクトを選んで紹介します。

## 使用技術
- JAVA
- JavaScript
- jQuery
- MyBaits
- Spring
- Oracle SQL
- Tomcat

***

## Table of Contents
- [Message](https://github.com/heerokim/Portfolio-Massage.git)
- [Blog](https://github.com/heerokim/Portfolio-BLOG.git)
- [Meeting](https://github.com/khrcodk/Portfolio-Meeting.git)

***

## [Message](https://github.com/heerokim/Portfolio-Massage.git)

### 要約

-登録した会員同士でメッセージをやりとりすることができる機能です。<br>
送信したい会員idを選択してメッセージを送信·受信メッセージを管理することができます。



### 詳しく

-このプロジェクトはSpringフレームワークを使用し、Javascript、Tomcat、Oracle SQL DBで構成構成されており、以下のように動作します。


![massage 001](https://user-images.githubusercontent.com/83088728/116214327-9063a000-a781-11eb-987f-b4b7d400e56b.jpeg)


1. 会員登録すると、DBに情報が保存されます。
2. ログインして希望のメッセージ確認、送信などのメニューを選択することができます。
3. メッセージを送信する時は、登録会員idを選択してメッセージを作成·転送します。
4. 受信メッセージを読み込むと、確認の可否を確認することができます。
5. 希望するメッセージを重要メッセージとして選択し、別途に管理することができます。


***

## [Blog](https://github.com/heerokim/Portfolio-BLOG.git)

### 要約

-ブログ形式で会員登録後、掲示板に投稿することができます。<br>
掲示文を作成すると、作成者の文を確認することができます。

### 詳しく

-このプロジェクトはSpringフレームワークを使用してCURDを基本として構成されており、
次のように動作します。

![blog 001](https://user-images.githubusercontent.com/83088728/116210443-d585d300-a77d-11eb-9e98-fbd90467cb19.jpeg)

1. 会員登録をしてデータはDBに情報が保存されます。 
2. ログインすると、登録された会員様のブログを選択できます。
3. ブログを選択すると掲示板で掲示した文章のリストが見られます。
4. ご希望の掲示板を選択、「いいね」ボタンを使って「いいね」をすることもできます。 
5. 作成者は、掲示板から掲示文を削除することもできます。



***

## [booking Meeting](https://github.com/heerokim/Portfolio-BLOG.git)

### 要約

-登録された会員が希望する日付と時間を選択し、他の人を招待することができます。<br>
ログインすると、会議の予約情報を確認またはキャンセルすることができます。

### 詳しく

-このプロジェクトはSpringフレームワークを使用してCURDを基本として構成されており、
次のように動作します。

![meeting 001](https://user-images.githubusercontent.com/83088728/116215291-81312200-a782-11eb-89dd-fedc994c4bd3.jpeg)

1. ログインすると、ご希望の会議室を選択して予約をすることができます。
2. 会議室を予約する時は、タイトルと日時を入力し、希望する参加者を選択することができます。
3. 予約または招待された会員は、私の会議リストから予約された会議を確認することができます。
4. キャンセルまたは欠席を選択すると、予約した会議がキャンセルまたは招待された会議が削除されます。 
5. ログアウトでログイン画面に戻ります。
