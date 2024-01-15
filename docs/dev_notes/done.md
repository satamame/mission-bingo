# 開発メモ - やったこと

1. 「速習 Laravel」に従って新規アプリを作った。
1. トップページのためのコントローラを作った。
    ```
    > php artisan make:controller TopController
    ```
1. routes/web.php を編集して TopController を返すようにした。
1. TopController で Blade テンプレートを使うようにした。
1. MySQL にデータベースを作って、.env に接続設定を書いた。
