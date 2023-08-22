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
- 2023-04-10 吉
- 2023-04-11 吉
- 2023-04-12 末吉
- 2023-04-13 大吉
- 2023-04-14 吉
- 2023-04-15 凶
- 2023-04-16 凶
- 2023-04-17 大吉
- 2023-04-18 凶
- 2023-04-19 凶
- 2023-04-20 吉
- 2023-04-21 凶
- 2023-04-22 凶
- 2023-04-23 凶
- 2023-04-24 吉
- 2023-04-25 吉
- 2023-04-26 大吉
- 2023-04-27 末小吉
- 2023-04-28 吉
- 2023-04-29 凶
- 2023-04-30 凶
- 2023-05-01 末吉
- 2023-05-02 吉
- 2023-05-03 大吉
- 2023-05-04 吉
- 2023-05-05 吉
- 2023-05-06 吉
- 2023-05-07 凶
- 2023-05-08 吉
- 2023-05-09 末吉
- 2023-05-10 吉
- 2023-05-11 半吉
- 2023-05-12 吉
- 2023-05-13 吉
- 2023-05-14 半吉
- 2023-05-15 吉
- 2023-05-16 凶
- 2023-05-17 吉
- 2023-05-18 凶
- 2023-05-19 大吉
- 2023-05-20 末小吉
- 2023-05-21 吉
- 2023-05-22 吉
- 2023-05-23 半吉
- 2023-05-24 凶
- 2023-05-25 吉
- 2023-05-26 吉
- 2023-05-27 大吉
- 2023-05-28 半吉
- 2023-05-29 吉
- 2023-05-30 半吉
- 2023-05-31 大吉
- 2023-06-01 吉
- 2023-06-02 凶
- 2023-06-03 凶
- 2023-06-04 吉
- 2023-06-05 吉
- 2023-06-06 大吉
- 2023-06-07 小吉
- 2023-06-08 吉
- 2023-06-09 吉
- 2023-06-10 大吉
- 2023-06-11 吉
- 2023-06-12 末吉
- 2023-06-13 吉
- 2023-06-14 大吉
- 2023-06-15 吉
- 2023-06-16 吉
- 2023-06-17 吉
- 2023-06-18 吉
- 2023-06-19 大吉
- 2023-06-20 末吉
- 2023-06-21 凶
- 2023-06-22 末吉
- 2023-06-23 吉
- 2023-06-24 吉
- 2023-06-25 大吉
- 2023-06-26 吉
- 2023-06-27 凶
- 2023-06-28 吉
- 2023-06-29 吉
- 2023-06-30 吉
- 2023-07-01 吉
- 2023-07-02 凶
- 2023-07-03 末吉
- 2023-07-04 吉
- 2023-07-05 吉
- 2023-07-06 末吉
- 2023-07-07 吉
- 2023-07-08 大吉
- 2023-07-09 吉
- 2023-07-10 大吉
- 2023-07-11 吉
- 2023-07-12 吉
- 2023-07-13 吉
- 2023-07-14 末吉
- 2023-07-15 凶
- 2023-07-16 吉
- 2023-07-17 吉
- 2023-07-18 半吉
- 2023-07-19 吉
- 2023-07-20 吉
- 2023-07-21 末小吉
- 2023-07-22 半吉
- 2023-07-23 凶
- 2023-07-24 半吉
- 2023-07-25 吉
- 2023-07-26 凶
- 2023-07-27 凶
- 2023-07-28 吉
- 2023-07-29 末吉
- 2023-07-30 小吉
- 2023-07-31 凶
- 2023-08-01 吉
- 2023-08-02 大吉
- 2023-08-03 大吉
- 2023-08-04 末吉
- 2023-08-05 半吉
- 2023-08-06 吉
- 2023-08-07 吉
- 2023-08-08 吉
- 2023-08-09 凶
- 2023-08-10 凶
- 2023-08-11 吉
- 2023-08-12 吉
- 2023-08-13 吉
- 2023-08-14 凶
- 2023-08-15 大吉
- 2023-08-16 吉
- 2023-08-17 凶
- 2023-08-18 大吉
- 2023-08-19 大吉
- 2023-08-20 吉
- 2023-08-21 末吉
- 2023-08-22 大吉
