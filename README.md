# 18-summer-internship-selection

1. XAMPP インストール  
    1. https://www.apachefriends.org/jp/download.html  
    ※MACユーザは、XAMPPとXAMPP-VMがありますが、XAMPPをダウンロードしてください。
1. Composer インストール  
    1. https://getcomposer.org
1. SourceTree インストール  
    1. https://ja.atlassian.com/software/sourcetree  
1. 本リポジトリをクローン（置く場所をXAMPPのhtdocにする）
1. httpd.confの編集
    1. DocumentRootを右記に変更 C:xampp/htdocs/プロジェクト名/public
1. XAMPP のphpMyAdminからログインし、「asiaquest」というDBを作る
1. .envの編集
    1. 【mysql】※xamppのmysql初期設定ユーザです。  
    user: 'root'  
    password: ''
1. ターミナルを起動し、アプリケーションを配置したディレクトリに移動する
1. 「composer install」コマンドを実行する
1. 「composer dump-autoload」を実行する
1. 「php artisan migrate --seed 」を実行する
1. 「php artisan key:generate 」を実行する
1. デモの画面が表示されることの確認
1. ■バグfix課題  
◆基本的な流れ  
bug_01_sampleをチェックアウト  
bug_01_sample_takeru_chihara　※(bug_01_sumple_あなたの名_あなたの性)  でブランチを作成してください。  
バグを修正する  
bug_01_sampleにプルリクエストを送信する  
上記を繰り返す  
◆修正内容  
bug01 「ビューに着目しよう」　バグを修正してください  ※「せい」と「めい」が表示されていません。  
bug02 「リレーションを意識しよう　１」　バグを修正してください  
bug03 「リレーションを意識しよう　２」　バグを修正してください  
bug04 「モデルクラスがよみこめない」　バグを修正してください  
bug05 「モデルクラス内でフォーマットを指定しよう」　誕生日と入社日を「Y年m月d日」の表示にしてください。  
bug06 「データの受け渡しはどこから？　１」　社員情報を表示してください  
bug07 「データの受け渡しはどこから？　２」　社員情報を表示してください  
bug08 「リクエストパラメータを見てみよう」　社員情報を表示してください（検索条件に部と課を入力すると表示されますが、未入力時には、ほかの条件に合致する社員情報を表示してください）  
bug09 EnployeeControllerに書いてあるコメントを参考に、どんなバグがあるかを考えて、修正してください。  


1. ■チャレンジタスク  
　task 1 社歴を表示してください  
　　〇年〇ヶ月  
　task 2 検索したときに対象件数を表示するようにしてください  
　task 3 年齢を範囲指定で検索できるようにしてください。  
　　〇歳～〇歳  
　task 4 ページネーションをつけてください  
　　20件ずつ表示して下さい  
　　ページネーターは１つ戻ると１つ進むだけでお願いします。  


