HTTP/0.9(HTTP/1.0以前)からHTTP/1.0、HTTP/1.1とどのように段階を踏んでいったのか

- HTTP/0.9(HTTP/1.0以前)
    - 1つのドキュメントのみしか送れない
    - content-typeなし(text/htmlのみ)
    - クライアント側から検索リクエストしか送信できなかった
    - 参照リクエストのみ(新規作成、更新、削除はできない)
- HTTP/1.0(1992~)
    - シンプル版(0.9互換モード)とフル機能版の2つのリクエストフォーマットがあった。
        - リクエストにメソッドが追加(GET)
        - リクエストにHTTPバージョン追加
        - リクエストにヘッダが追加(Host, UserAgent, Accept)
        - レスポンスにレスポンスにHTTP verと、ステータスコード
        - レスポンスにリクエストと同じ形式のヘッダが含まれるように
    - HTTP/1.0は電子メールや、ニュースグループを参考に進化した
- まとめ
    - HTTPの基礎となる、4つのデータの入れ物
        - メソッドとパス
        - ヘッダ
        - ボディ
        - ステータスコード


