# infra-learning-log

Hands-on learning logs for Linux, AWS, and Web

### 2025-12-16

What I did:

* Created my first GitHub repository and README

What I learned:

* A repository is a place to record work and changes, not just finished code

Issues / Questions:

* How to connect this repo with my local environment



\- 2025-12-16: Connected local environment with GitHub
今日やったことの振り返り（2025-12-16）

今日は、GitHubとローカル環境を実際に接続し、
**「コードや記録をローカルで作り、GitHubに反映する一連の流れ」**を一通り体験した。

最初に行ったのは、GitHub上でリポジトリを作成することだった。
infra-learning-log という名前のリポジトリを作り、READMEを用意して、
この場所を「学習ログを蓄積する拠点」にする方針を決めた。

次に、ローカル環境側の準備として Git for Windows をインストールした。
Git Bash を使い、Gitが正しく動作しているかを git --version で確認。
この時点で、「GitはWeb上のものではなく、ローカルで使う道具」という理解がはっきりした。

その後、作業用ディレクトリとして github フォルダを作成し、
GitHub上のリポジトリを git clone でローカルにコピーした。
これにより、GitHub上のリポジトリと同一の内容がPC内に存在する状態を作った。

ローカルにコピーしたREADMEを編集し、
変更内容を Git に認識させるために git add を実行。
続いて git commit を行おうとした際、
Gitに「誰がこの変更を行ったのか」を登録する必要があることを学び、
user.name と user.email を設定した。

設定後、再度 git commit を実行し、
ローカルでの変更を履歴として確定させた。

最後に git push を実行すると、GitHubの認証画面が表示され、
ブラウザ経由でログイン・認証を行った。
認証が成功した後、ローカルで行った変更がGitHub上のリポジトリに反映されていることを
ブラウザで確認し、ローカル → Git → GitHub の往復が成立したことを確認できた。

今日得た理解

GitHubは「操作する場所」ではなく「成果を置く場所」

Gitはローカルで履歴を管理するための道具

clone → edit → add → commit → push が基本の流れ

エラーや詰まりは「失敗」ではなく、初回に必ず通る手順確認

今日の到達点

今日の作業によって、
GitHubを眺める段階から、GitHubに成果を書き戻せる段階に進んだ。

今後は、このリポジトリに
学習ログ・思考メモ・詰まりポイントを積み上げていく。
