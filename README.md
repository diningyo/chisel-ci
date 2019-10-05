# chisel-ci
ChiselのCI環境を構築するためのお試し環境

## とりあえずお試し。

よく分からずに`blank.yaml`を作ってみたけどActionsののページに何も起こらず。。。

## もう一回トライ

最初は"Start Commit"を押した際にプルリクを使った。
その後にマージをした所設定用のYAMLファイルがリポジトリのルート直下に生成されていた。
もう一度セットアップをしてみたと所".github/workflows"の下に"main.yaml"が生成されていた。

![再度セットアップをトライした際の画面キャプチャ](img/github_actions_setup.png)

この状態でコミットしてプッシュしてみる。

なんか動いた！

![プッシュ時のactionsの画面キャプチャ](img/github_actions_run.png)

タスクの詳細を開いてみると" successful 12 minutes ago in 4s "と出て成功していた。

![CIタスクの詳細](img/github_actions_success.png)