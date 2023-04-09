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
- 2023-01-06 凶
- 2023-01-07 大吉
- 2023-01-08 大吉
- 2023-01-09 吉
- 2023-01-10 末吉
- 2023-01-11 吉
- 2023-01-12 吉
- 2023-01-13 吉
- 2023-01-14 大吉
- 2023-01-15 凶
- 2023-01-16 凶
- 2023-01-17 大吉
- 2023-01-18 末小吉
- 2023-01-19 凶
- 2023-01-20 大吉
- 2023-01-21 吉
- 2023-01-22 吉
- 2023-01-23 吉
- 2023-01-24 大吉
- 2023-01-25 吉
- 2023-01-26 凶
- 2023-01-27 吉
- 2023-01-28 半吉
- 2023-01-29 末吉
- 2023-01-30 凶
- 2023-01-31 半吉
- 2023-02-01 凶
- 2023-02-02 大吉
- 2023-02-03 凶
- 2023-02-04 末小吉
- 2023-02-05 吉
- 2023-02-06 吉
- 2023-02-07 吉
- 2023-02-08 凶
- 2023-02-09 小吉
- 2023-02-10 小吉
- 2023-02-11 末吉
- 2023-02-12 大吉
- 2023-02-13 吉
- 2023-02-14 吉
- 2023-02-15 大吉
- 2023-02-16 凶
- 2023-02-17 凶
- 2023-02-18 大吉
- 2023-02-19 大吉
- 2023-02-20 凶
- 2023-02-21 半吉
- 2023-02-22 吉
- 2023-02-23 大吉
- 2023-02-24 小吉
- 2023-02-25 大吉
- 2023-02-26 吉
- 2023-02-27 凶
- 2023-02-28 吉
- 2023-03-01 大吉
- 2023-03-02 吉
- 2023-03-03 凶
- 2023-03-04 吉
- 2023-03-05 吉
- 2023-03-06 凶
- 2023-03-07 大吉
- 2023-03-08 凶
- 2023-03-09 末小吉
- 2023-03-10 凶
- 2023-03-11 凶
- 2023-03-12 吉
- 2023-03-13 大吉
- 2023-03-14 吉
- 2023-03-15 吉
- 2023-03-16 吉
- 2023-03-17 吉
- 2023-03-18 凶
- 2023-03-19 吉
- 2023-03-20 凶
- 2023-03-21 吉
- 2023-03-22 末吉
- 2023-03-23 吉
- 2023-03-24 吉
- 2023-03-25 凶
- 2023-03-26 凶
- 2023-03-27 吉
- 2023-03-28 吉
- 2023-03-29 吉
- 2023-03-30 吉
- 2023-03-31 凶
- 2023-04-01 凶
- 2023-04-02 大吉
- 2023-04-03 大吉
- 2023-04-04 吉
- 2023-04-05 大吉
- 2023-04-06 吉
- 2023-04-07 大吉
- 2023-04-08 凶
- 2023-04-09 吉
