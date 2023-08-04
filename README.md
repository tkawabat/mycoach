# 環境構築

* 事前にインストールするもの
    * Docker
    * direnv
        ```
        $ brew install direnv
        ```

* 初回に一回だけやること
    ```
    # 環境変数の読み込み
    $ direnv allow

    # 使用するIPにエイリアスを貼る
    $ sudo ifconfig lo0 alias 127.0.0.3 up
    ```

# Database
* sqldef
    * スキーマ管理ツール
    * インストール
        ```
        $ brew install sqldef/sqldef/mysqldef
        ```
    * 