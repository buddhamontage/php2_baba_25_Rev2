#PHP02課題

##PHPとMysql利用したログイン認証アプリ
###①課題内容
ログイン認証及び個人登録情報の更新/削除

操作手順
・MAMPのhtdocsフォルダへphp2_baba_25ファイルを配置
・MAMPのMysqlにuser_dbの名前でデータベース作成
・user_db内user_tableを作成
・tableにカラム５つ作成
・id、u_name、u_id、u_pw,life_flg,indateの各フォームを作成
・事前に任意のユーザ情報を登録
・localhostからindex.phpへアクセス
・登録されているユーザ情報のu_id名とu_pwでログイン
・情報登録ページに遷移後に、情報をクリックすると個人情報変更ページへ移動
・削除ボタンを押すとデータ削除

###②工夫した点
・ページ遷移後のsession keyでログイン情報を認証

###③質問・疑問（あれば）
山崎学長の講義動画では、別タブを開いてselect.phpを開くとsession keyが違うためエラーになるが、実際にchromでやるとsession keyに変更が起きないため問題なくページ遷移ができる。
これは単純にchromのキャッシュの設定の違いでしょうか。
