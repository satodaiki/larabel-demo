## 概要

Larabelの勉強用リポジトリ

参考書籍はこれ。

[はじめてのLaravel5.7入門: PHPフレームワークLaravel5.7とPaizaCloudを使って10分でWebサービスを作る](https://www.amazon.co.jp/dp/B07HG2ZT15/ref=cm_sw_em_r_mt_dp_U_OfelDb2DH6T3V)

これをlocalでできるように構築した。

### Laravelの起動

起動コマンドは以下の通り。

```
$ php artisan serve
```

### DBにMySQLを使用する際の注意点

デフォルトだと認証設定がLaravelに対応していないので、以下の記事を参考にしてmysqlの設定を修正する必要あり。

[MySQL8.0 認証方式を変更する(Laravel5)](https://qiita.com/ucan-lab/items/3ae911b7e13287a5b917)
