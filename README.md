# showks-docs

[showks-keycloak-user-operator](https://github.com/cloudnativedaysjp/showks-keycloak-user-operator)

カスタムリソースでKeyCloakのユーザを操作するコントローラーです。

[showks-concourseci-pipeline-operator](https://github.com/cloudnativedaysjp/showks-concourseci-pipeline-operator)

カスタムリソースでConcourseのパイプラインを操作するコントローラーです。ConcourseのAPIを叩くのではなく、コンテナイメージにfly(concourseを操作するためのCLIコマンド)を含め、コントローラーから呼び出す形で実装してみました。

[showks-github-repository-operator](https://github.com/cloudnativedaysjp/showks-github-repository-operator)

カスタムリソースでGitHubのリポジトリを操作するコントローラーです。リポジトリのコラボレータやWebHook、ブランチプロテクションを設定したり、ベースとなるリポジトリを指定してテンプレートとして利用することができます。