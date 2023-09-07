# DMM Webサービス APIリファレンス
## 概要
「DMM Webサービス」はDMMが保有するデータベースを外部から利用するためのWeb APIを提供するサービスです。このリポジトリでは、DMMが提供してるAPIリファレンスをOpenAPIの様式でリライトしたものを公開しています。非公式のものであり、利用は自己責任にてお願いします。
リファレンスは[こちら](https://mgmyst.github.io/dmm-web-service-api-reference/)です。

APIの正確な仕様が知りたい場合には[公式のリファレンス](https://affiliate.dmm.com/api/)を参照してください。

## 構成ファイル解説
### api-reference.json
OpenAPIの仕様に則りjson形式で記述された`DMM Webサービス APIリファレンス`になります。Swaggerなどでインポートすれば、API仕様の確認に加えて実際にテストすることも可能です。

[api-reference.json](api-reference.json)

### index.html
`api-reference.json`をもとに[Redoc](https://github.com/Redocly/redoc)で作成されたhtml版のリファレンスです。
[GithubPagesでホスト](https://mgmyst.github.io/dmm-web-service-api-reference/)しています。

[index.html](index.html)
