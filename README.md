# write-code-everyday-bot

## 解説

- GitHub Actions を使うサンプルです
  - CIから朝9時に今日の運勢をこの文書に末尾へ追記し、自動的にコミットしてpushします。
  - 設定方法は製作者様の[Qiitaの記事](https://qiita.com/ykhirao/items/65fee829ee0478187027)を参照して下さい。

- push時の認証方法について注意事項
  - 本サンプルでは、pushする手段としてHTTPSを使用しています。
  - ただしパスワード認証は廃止されたため、secretsにパスワードを使用すると認証エラーになります。
  - 代替手段としてアクセストークンを発行し、それを環境変数のsecretsに登録してください。
    - [自身のアイコン] -> [Settings] -> [Developer settings] -> [Personal access tokens] -> [Tokens(classic)] -> [Generate new token] -> トークン生成
    - [このリポジトリ] -> [Settings] -> [Secrets and variables] -> [Action] -> [Repository secrets] -> MY_SECRETを更新

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
- 2023-08-23 末吉
- 2023-08-24 末小吉
- 2023-08-25 凶
- 2023-08-26 凶
- 2023-08-27 凶
- 2023-08-28 凶
- 2023-08-29 末吉
- 2023-08-30 吉
- 2023-08-31 凶
- 2023-09-01 末吉
- 2023-09-02 末吉
- 2023-09-03 大吉
- 2023-09-04 凶
- 2023-09-05 凶
- 2023-09-06 凶
- 2023-09-07 小吉
- 2023-09-08 凶
- 2023-09-09 吉
- 2023-09-10 吉
- 2023-09-11 凶
- 2023-09-12 小吉
- 2023-09-13 半吉
- 2023-09-14 大吉
- 2023-09-15 大吉
- 2023-09-16 吉
- 2023-09-17 凶
- 2023-09-18 凶
- 2023-09-19 吉
- 2023-09-20 凶
- 2023-09-21 吉
- 2023-09-22 末吉
- 2023-09-23 小吉
- 2023-09-24 凶
- 2023-09-25 凶
- 2023-09-26 凶
- 2023-09-27 吉
- 2023-09-28 末吉
- 2023-09-29 凶
- 2023-09-30 吉
- 2023-10-01 凶
- 2023-10-02 小吉
- 2023-10-03 吉
- 2023-10-04 吉
- 2023-10-05 吉
- 2023-10-06 吉
- 2023-10-07 吉
- 2023-10-08 吉
- 2023-10-09 大吉
- 2023-10-10 吉
- 2023-10-11 凶
- 2023-10-12 凶
- 2023-10-13 末吉
- 2023-10-14 大吉
- 2023-10-15 小吉
- 2023-10-16 大吉
- 2023-10-17 凶
- 2023-10-18 凶
- 2023-10-19 末吉
- 2023-10-20 吉
- 2023-10-21 凶
- 2023-10-22 吉
- 2023-10-23 凶
- 2023-10-24 凶
- 2023-10-25 凶
- 2023-10-26 大吉
- 2023-10-27 吉
- 2023-10-28 凶
- 2023-10-29 凶
- 2023-10-30 凶
- 2023-10-31 吉
- 2023-11-01 凶
- 2023-11-02 凶
- 2023-11-03 大吉
- 2023-11-04 凶
- 2023-11-05 大吉
- 2023-11-06 吉
- 2023-11-07 末吉
- 2023-11-08 吉
- 2023-11-09 凶
- 2023-11-10 吉
- 2023-11-11 凶
- 2023-11-12 吉
- 2023-11-13 凶
- 2023-11-14 吉
- 2023-11-15 半吉
- 2023-11-16 凶
- 2023-11-17 末小吉
- 2023-11-18 大吉
- 2023-11-19 凶
- 2023-11-20 末小吉
- 2023-11-21 吉
- 2023-11-22 大吉
- 2023-11-23 大吉
- 2023-11-24 吉
- 2023-11-25 末吉
- 2023-11-26 吉
- 2023-11-27 凶
- 2023-11-28 末吉
- 2023-11-29 末小吉
- 2023-11-30 吉
- 2023-12-01 吉
- 2023-12-02 大吉
- 2023-12-03 大吉
- 2023-12-04 吉
- 2023-12-05 大吉
- 2023-12-06 吉
- 2023-12-07 吉
- 2023-12-08 吉
- 2023-12-09 大吉
- 2023-12-10 吉
- 2023-12-11 凶
- 2023-12-12 小吉
- 2023-12-13 凶
- 2023-12-14 吉
- 2023-12-15 凶
- 2023-12-16 末吉
- 2023-12-17 吉
- 2023-12-18 半吉
- 2023-12-19 凶
- 2023-12-20 吉
- 2023-12-21 吉
- 2023-12-22 凶
- 2023-12-23 吉
- 2023-12-24 凶
- 2023-12-25 凶
- 2023-12-26 末小吉
- 2023-12-27 半吉
- 2023-12-28 凶
- 2023-12-29 凶
- 2023-12-30 凶
- 2024-02-04 半吉
- 2024-02-04 大吉
- 2024-02-05 半吉
- 2024-02-06 吉
- 2024-02-07 凶
- 2024-02-08 大吉
- 2024-02-09 小吉
- 2024-02-10 凶
- 2024-02-11 吉
- 2024-02-12 吉
- 2024-02-13 凶
- 2024-02-14 大吉
- 2024-02-15 凶
- 2024-02-16 半吉
- 2024-02-17 凶
- 2024-02-18 吉
- 2024-02-19 凶
- 2024-02-20 凶
- 2024-02-21 吉
- 2024-02-22 半吉
- 2024-02-23 凶
- 2024-02-24 凶
- 2024-02-25 吉
- 2024-02-26 吉
- 2024-02-27 吉
- 2024-02-28 末吉
- 2024-02-29 大吉
- 2024-03-01 吉
- 2024-03-02 吉
- 2024-03-03 吉
- 2024-03-04 吉
- 2024-03-05 末吉
- 2024-03-06 末小吉
- 2024-03-07 凶
- 2024-03-08 凶
- 2024-03-09 大吉
- 2024-03-10 凶
- 2024-03-11 吉
- 2024-03-12 吉
- 2024-03-13 凶
- 2024-03-14 吉
- 2024-03-15 半吉
- 2024-03-16 末吉
- 2024-03-17 凶
- 2024-03-18 吉
- 2024-03-19 吉
- 2024-03-20 大吉
- 2024-03-21 大吉
- 2024-03-22 凶
- 2024-03-23 小吉
- 2024-03-24 凶
- 2024-03-25 吉
- 2024-03-26 凶
- 2024-03-27 凶
- 2024-03-28 大吉
- 2024-03-29 吉
- 2024-03-30 凶
- 2024-03-31 大吉
- 2024-04-01 吉
- 2024-04-02 凶
- 2024-04-03 大吉
- 2024-04-04 大吉
- 2024-04-05 半吉
- 2024-04-06 吉
- 2024-04-07 吉
- 2024-04-08 凶
- 2024-04-09 半吉
- 2024-04-10 大吉
- 2024-04-11 凶
- 2024-04-12 大吉
- 2024-04-13 吉
- 2024-04-14 凶
- 2024-04-15 凶
- 2024-04-16 小吉
- 2024-04-17 末吉
- 2024-04-18 吉
- 2024-04-19 吉
- 2024-04-20 吉
- 2024-04-21 吉
- 2024-04-22 凶
- 2024-04-23 凶
- 2024-04-24 凶
- 2024-04-25 凶
- 2024-04-26 吉
- 2024-04-27 吉
- 2024-04-28 吉
- 2024-04-29 小吉
- 2024-04-30 凶
- 2024-05-01 凶
- 2024-05-02 大吉
- 2024-05-03 吉
- 2024-05-04 半吉
- 2024-05-06 大吉
- 2024-05-07 吉
- 2024-05-08 大吉
- 2024-05-09 凶
- 2024-05-10 凶
- 2024-05-11 吉
- 2024-05-12 大吉
- 2024-05-13 吉
- 2024-05-14 末吉
- 2024-05-15 吉
- 2024-05-16 凶
- 2024-05-17 吉
- 2024-05-18 吉
- 2024-05-19 半吉
- 2024-05-20 大吉
- 2024-05-21 半吉
- 2024-05-22 凶
- 2024-05-23 凶
- 2024-05-24 凶
- 2024-05-25 大吉
- 2024-05-26 凶
- 2024-05-27 吉
- 2024-05-28 吉
- 2024-05-29 凶
- 2024-05-30 凶
- 2024-05-31 吉
- 2024-06-01 吉
- 2024-06-02 凶
- 2024-06-03 凶
- 2024-06-04 大吉
- 2024-06-05 末小吉
- 2024-06-06 吉
- 2024-06-07 大吉
- 2024-06-08 大吉
- 2024-06-09 凶
- 2024-06-10 吉
- 2024-06-11 凶
- 2024-06-12 凶
- 2024-06-13 吉
- 2024-06-14 凶
- 2024-06-15 凶
- 2024-06-16 小吉
- 2024-06-17 大吉
- 2024-06-18 末吉
- 2024-06-19 大吉
- 2024-06-20 大吉
- 2024-06-21 末小吉
- 2024-06-22 大吉
- 2024-06-23 吉
- 2024-06-24 吉
- 2024-06-25 小吉
- 2024-06-26 大吉
- 2024-06-27 凶
- 2024-06-28 吉
- 2024-06-29 凶
- 2024-06-30 吉
- 2024-07-01 凶
- 2024-07-02 凶
- 2024-07-03 末吉
- 2024-07-04 凶
- 2024-07-05 吉
- 2024-07-06 凶
- 2024-07-07 半吉
- 2024-07-08 半吉
- 2024-07-09 大吉
- 2024-07-10 吉
- 2024-07-11 大吉
- 2024-07-12 大吉
- 2024-07-13 吉
- 2024-07-14 大吉
- 2024-07-15 半吉
- 2024-07-16 半吉
- 2024-07-17 大吉
- 2024-07-18 吉
- 2024-07-20 吉
- 2024-07-20 吉
- 2024-07-21 凶
- 2024-07-22 吉
- 2024-07-23 大吉
- 2024-07-24 吉
- 2024-07-25 吉
- 2024-07-26 凶
- 2024-07-27 凶
- 2024-07-28 凶
- 2024-07-29 半吉
- 2024-07-30 凶
- 2024-07-31 吉
- 2024-08-01 末吉
- 2024-08-02 小吉
- 2024-08-03 大吉
- 2024-08-04 末小吉
- 2024-08-14 凶
- 2024-08-15 大吉
- 2024-08-16 末小吉
- 2024-08-17 小吉
- 2024-08-18 末小吉
- 2024-08-19 凶
- 2024-08-20 小吉
- 2024-08-21 凶
- 2024-08-22 吉
- 2024-08-23 凶
- 2024-08-24 凶
- 2024-08-25 大吉
- 2024-08-26 吉
- 2024-08-27 吉
- 2024-08-28 凶
- 2024-08-29 凶
- 2024-08-30 凶
- 2024-08-31 小吉
- 2024-09-01 大吉
- 2024-09-02 吉
- 2024-09-03 半吉
- 2024-09-04 大吉
- 2024-09-05 吉
- 2024-09-06 小吉
- 2024-09-07 吉
- 2024-09-16 吉
- 2024-09-17 凶
- 2024-09-18 末吉
- 2024-09-19 大吉
- 2024-09-20 凶
- 2024-09-21 吉
- 2024-09-22 吉
- 2024-09-23 大吉
- 2024-09-24 凶
- 2024-09-25 吉
- 2024-09-26 凶
- 2024-09-27 吉
- 2024-09-28 凶
- 2024-09-29 大吉
- 2024-09-30 凶
- 2024-10-01 大吉
- 2024-10-02 凶
- 2024-10-03 末小吉
- 2024-10-04 吉
- 2024-10-05 吉
- 2024-10-06 吉
- 2024-10-07 大吉
- 2024-10-08 吉
- 2024-10-09 吉
- 2024-10-10 大吉
- 2024-10-11 凶
- 2024-10-12 吉
- 2024-10-13 大吉
- 2024-10-14 凶
- 2024-10-15 末吉
- 2024-10-16 末吉
- 2024-10-17 吉
- 2024-10-18 大吉
- 2024-10-19 凶
- 2024-10-20 吉
- 2024-10-21 半吉
- 2024-10-22 大吉
- 2024-10-23 末小吉
- 2024-10-24 末吉
- 2024-10-25 小吉
- 2024-10-26 凶
- 2024-10-27 大吉
- 2024-10-28 凶
- 2024-10-29 吉
- 2024-10-30 凶
- 2024-10-31 半吉
- 2024-11-01 凶
- 2024-11-02 凶
- 2024-11-03 末小吉
- 2024-11-04 小吉
- 2024-11-05 吉
- 2024-11-06 吉
- 2024-11-07 半吉
- 2024-11-08 凶
- 2024-11-09 末吉
- 2024-11-10 大吉
- 2024-11-11 凶
- 2025-01-04 吉
- 2025-01-05 大吉
- 2025-01-06 凶
- 2025-01-07 大吉
- 2025-01-08 凶
- 2025-01-09 凶
- 2025-01-10 凶
- 2025-01-11 吉
- 2025-01-12 半吉
- 2025-01-13 末吉
- 2025-01-15 吉
- 2025-01-16 大吉
- 2025-01-17 凶
- 2025-01-18 凶
- 2025-01-19 吉
- 2025-01-20 凶
- 2025-01-21 吉
- 2025-01-22 吉
- 2025-01-23 凶
- 2025-01-24 凶
- 2025-01-25 吉
- 2025-01-26 吉
- 2025-01-27 半吉
- 2025-01-28 凶
- 2025-01-29 末吉
- 2025-01-30 大吉
- 2025-01-31 吉
- 2025-02-01 凶
- 2025-02-02 凶
- 2025-02-03 大吉
- 2025-02-04 凶
- 2025-02-05 末吉
- 2025-02-06 大吉
- 2025-02-07 吉
- 2025-02-08 末吉
- 2025-02-09 大吉
- 2025-02-10 末吉
- 2025-02-11 吉
- 2025-02-12 末吉
- 2025-02-13 小吉
- 2025-02-14 凶
- 2025-02-15 吉
- 2025-02-16 末吉
- 2025-02-17 大吉
- 2025-02-18 大吉
- 2025-02-19 小吉
- 2025-02-20 半吉
- 2025-02-21 吉
- 2025-02-22 大吉
- 2025-02-23 吉
- 2025-02-24 凶
- 2025-02-25 小吉
- 2025-02-26 凶
- 2025-02-27 吉
- 2025-02-28 吉
- 2025-03-01 凶
- 2025-03-02 吉
- 2025-03-03 大吉
- 2025-03-04 凶
- 2025-03-05 末吉
- 2025-03-06 半吉
- 2025-03-07 吉
- 2025-03-08 末吉
- 2025-03-09 吉
- 2025-03-10 凶
- 2025-03-11 吉
- 2025-03-12 凶
- 2025-03-13 凶
- 2025-03-14 凶
- 2025-03-15 凶
- 2025-03-16 半吉
- 2025-03-17 吉
- 2025-03-18 吉
- 2025-03-19 大吉
- 2025-03-20 大吉
- 2025-03-21 凶
- 2025-03-22 凶
- 2025-03-23 凶
- 2025-03-24 吉
- 2025-03-25 凶
- 2025-03-26 吉
- 2025-03-27 凶
- 2025-03-28 大吉
- 2025-03-29 小吉
- 2025-03-30 吉
- 2025-03-31 吉
- 2025-04-01 末吉
- 2025-04-02 末小吉
- 2025-04-03 凶
- 2025-04-04 末吉
- 2025-04-05 吉
- 2025-04-06 半吉
- 2025-04-07 凶
- 2025-04-08 吉
- 2025-04-09 大吉
- 2025-04-10 凶
- 2025-04-11 凶
- 2025-04-12 大吉
