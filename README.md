## 田中

AIを活用した業務システムの開発と、プロジェクトの進行。  
要件の聞き取りから設計・テスト・保守まで、決定の記録と自動テストを残して進めます。

### 主な仕事

**運送会社の業務システム**（受託・2026年10月から本番運用中）  
Google スプレッドシートと Google Apps Script で、日々の業務を一連の仕組みにしました。  
工程：聞き取り・要件整理・設計・開発・確認・本番への切り替え・保守／自動テスト約400本  
※お客様の名前・画面・コードは、守秘のため公開していません。

**接骨院向けAIチャットボット**（お渡し済み）  
LINE で、よくある質問への回答と予約の受付・確認を24時間行い、答えられない内容はスタッフへ知らせます。  
[動画を見る](https://youtu.be/GTTvPerFMgY)

**GASの見本「予定の盤」**（公開中）  
Google スプレッドシートの予定を、将棋の駒のようにつかんで動かせる画面です。画面はすぐ動き、裏で Google Apps Script が表に書きます。重なり・ほかの日への移動・2人が同時に動かした時の食い違いも防ぎます。自動テスト121本と、わざと壊して確かめた54通りを一緒に載せています。  
[触ってみる](https://script.google.com/macros/s/AKfycbzf4gh0BJ3rWZpaxErrB11fhszA4jX-DABXvpLBJQb9XNgtD9TyF0wUzrt3ig6dFUCPTA/exec)・[コード](https://github.com/tanaka264839-cmyk/koma-ban)

**Androidアプリ「StepLock」**（Google Play で公開中）  
歩いた分だけスマホが使える、スマホの使いすぎを防ぐアプリです。  
こういうアプリは、今やAIでだれでも作れます。だけど、0時をまたいでも、電源を入れ直しても、許可を後から切っても崩れない作りと、それを確かめた証拠までそろえるのは、今も簡単ではありません。  
コードは、公開中の版をもとに役目ごとに作り直し、決まりを自動テスト182本で固めた物です。決めた理由と確かめた結果も、一緒に載せています。  
[Google Play](https://play.google.com/store/apps/details?id=com.shosoku.steplock)・[コード](https://github.com/tanaka264839-cmyk/StepLock)

**Webサービス「負け犬の癒し」**（公開中）  
名前を出さずに、うまくいかなかったことを書き込める掲示板です。いいねの数は出さず、人を傷つける言葉は送る前に止めます。Python と SQLite で作り、自動テスト161本で固めています。  
[サイト](https://makeinu.net/)・[紹介記事](https://note.com/tanaka_hagatatsu/n/n38aff8cecfa2)・[コード](https://github.com/tanaka264839-cmyk/makeinu)

**帳票OCRの業務ツール**（自主開発）  
請求書・日報など紙の帳票の写真やPDFをAIで読み取り、人が原票と見比べて確認・承認した分だけExcelに出します。請求書10枚の転記が、25分から5分になりました。  
[紹介記事](https://note.com/tanaka_hagatatsu/n/n310e3494219c)

**AIの戸締まり表**（Windows のアプリ）  
AIに任せていることを12項目に分け、どこが開いているかを1枚で見せます。閉める前に、止まる作業と、閉めても防げないことを見せます。  
[紹介記事](https://note.com/tanaka_hagatatsu/n/n3b0299fa6462)

**PayPayの履歴で作る家計簿**  
PayPayアプリの取引履歴を Google ドライブに入れるだけで、Google スプレッドシートの家計簿に入り、費目に自動で分かれます。明細は、使う人のスプレッドシートの中だけで扱います。  
[紹介記事](https://note.com/tanaka_hagatatsu/n/nad963332df20)

### 進め方

- 聞き取った要望と、決めた理由を記録に残す
- 直すたびに自動テストを通してから、本番に入れる
- 納品の後は、お客様だけで回せる形を目指す

### 技術

Google Apps Script・JavaScript・Python・Kotlin  
開発には生成AI（Claude Code・Codex）を使い、何を作るか・設計・確認は人が判断します。
