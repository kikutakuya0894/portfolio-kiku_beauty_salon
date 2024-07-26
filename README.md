# 【ホームページ＆予約管理システム】
実家の美容室で運用する予定で作った予約管理システムと、予約が確認できるホームページです。<br>
管理ページでは予約の[追加][更新][削除]などができます。<br>
ホームページではカレンダーがあり、予約ができるかの確認ができます。<br>
製作期間は約3ヶ月です。<br>
<br>

菊美容室のホームページ<br>
https://xn--wbttbx74p4sd.com/home <br>

# 使用技術
・PHP <br>
・Laravel <br>
・Bootstrap<br>
・JavaScript<br>
・jquery<br>

# こだわったポイント
　ユーザビリティを高めるために、予約の追加などの処理は<br>
　JavaScriptやjqueryを使ってすべて非同期処理で作りました。<br>

# 苦労したポイント
　予約が重複したときの判定処理や、予約の時間が赤くなる処理、<br>
　ホームページのカレンダーの処理などの時間や日付の計算処理を<br>
　作るのに苦労しました。<br>
　

# 機能
【管理ページ】 <br>
予約の管理やカットやパーマなどのメニューの編集ができます。


【初期画面】
![](images/initial_page.png "")
・予約管理ページ、メニュー管理ページ、アカウント管理ページなどのページに遷移できるページです。<br>
<br>
<br>

【予約カレンダー初期画面】
![](images/calendar_initial_page.png "")
・予約管理をするページです。<br>
　日付をクリックすると予約画面が現れます。<br>
<br>
<br>

【予約入力画面_1】
![](images/calendar_reservation_page1.png "")
・予約の開始時間を選択する画面です。<br>
<br>
<br>

【予約入力画面_2】
![](images/calendar_reservation_page2.png "")
・予約の詳細を入力する画面です。<br>
　[予約者名][電話番号][カテゴリー][オフセット]が入力できます。<br>
<br>
<br>

【予約入力画面_3】
![](images/calendar_reservation_page3.png "")
・カテゴリーを選択する画面です。<br>
　選択するカテゴリーで終了時間が自動で変わります。<br>
<br>
<br>

【予約入力画面_4】
![](images/calendar_reservation_page4.png "")

<br>
<br>

【予約入力画面_5】
![](images/calendar_reservation_page5.png "")
・予約完了後、予約の時間は赤く表示されます。<br>
<br>
<br>

【予約カレンダー_予約後】
![](images/calendar_initial_page2.png "")
・予約の情報はカレンダーにも表示されます。<br>
<br>
<br>

【メニュー管理画面】
![](images/menu_page.png "")
・メニューの[追加][更新][削除]ができるページです。<br>
　[メニュー名][カテゴリー][金額]が入力できます。<br>
　カテゴリー編集ページにも遷移できます。<br>
<br>
<br>

【カテゴリー編集画面】
![](images/category_page.png "")
・カテゴリーの[追加][更新][削除]ができるページです。<br>
　[カテゴリー名][所要時間][カテゴリーナンバー(表示する順番)]を入力できます。<br>
<br>
<br>

【ホームページ】 <br>
予約ができるかの確認や料金の確認ができます。
<br>

【ホームページ_1】 
![](images/home_page1.png "")

<br>
<br>

【ホームページ_2】 
![](images/home_page2.png "")
・美容室の営業日カレンダーです。<br>
　クリックすると予約ができるか確認ができます。<br>
<br>
<br>

【ホームページ_3】 
![](images/home_page3.png "")
・予約ができるか確認ができます。<br>
　[〇]予約ができる<br>
　[×]予約ができない<br>
<br>
<br>

