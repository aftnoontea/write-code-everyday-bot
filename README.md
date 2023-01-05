# write-code-everyday-bot

## 解説

- GitHub Actions を使うサンプルです
  - CIから朝9時に今日の運勢をこの文書に末尾へ追記し、自動的にコミットしてpushします。
  - 設定方法は製作者様の[Qiitaの記事](https://qiita.com/ykhirao/items/65fee829ee0478187027)を参照して下さい。

- push時の認証方法について注意事項
  - 本サンプルでは、pushする手段としてHTTPSを使用しています。
  - ただしパスワード認証は廃止されたため、secretsにパスワードを使用すると認証エラーになります。
  - 代替手段としてアクセストークンを発行し、それを環境変数のsecretsに登録してください。

## 今日の運勢（自動追記）
- 2023-01-03 吉
- 2023-01-04 吉
- 2023-01-05 凶
