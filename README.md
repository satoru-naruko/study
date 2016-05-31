git コミットまでの流れおさらい

1. リモートリポジトリ作成(web上に作成)
2. リモートリポジトリをもってきたいフォルダに下記コマンド
% git init
3. リモートリポジトリを追加
git remote add origin git@github.com:satoru-naruko/study
4. ローカル環境にファイルを追加する（下記のコマンド）
% git add README.md
5. コミット(ローカル環境) （下記のコマンド） ""はコメント
% git commit -m "first commit"
6. リモートリポジトリのmasterに反映
% git push -u origin master
