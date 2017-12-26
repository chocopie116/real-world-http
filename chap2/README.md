# chap2 HTTP/1.0の機能とそれに対応するブラウザの機能

- x-www-form-urlencoded
- multipart/form-data
    - ファイル送信が可能
- コンテントネゴシエーション
    - Accept
    - Accept-Language
    - Accept-Charset
    - Accept-Encoding
- クッキー
- プロキシ
    - プロキシ(通信内容の理解・コンテンツの改変・originサーバーの代わりレスポンス返却したり)
    - ゲートウェイ(通信内容をそのまま転送。内容の改善はなし)
- キャッシュ
    - 更新日時によるキャッシュ
        - Last-Modified,
        - If-Modified-Since
    - Expires(サーバーへのリクエストをせずにlocalのキャッシュを利用)       
    - Pragma:no-cache
    - ETag
    - Cache-Control(サーバーのレスポンスヘッダ)
        - public
        - private
        - max-age=n
        - x-maxage=n
        - no-cache
        - no-store
    - Cache-Control(クライアントからのリクエストヘッダ)
        - no-cache
        - no-store
        - max-age
        - max-stale
        - min-fresh
        - no-transform
        - only-if-cached
- Vary
- Referrer

        
    
