# dash-docset-optuna
Generate docset for [Dash for macOS](https://kapeli.com/dash) from the latest release of  [Optuna](https://github.com/optuna/optuna).

The following jobs are automated by GitHub Actions. See [docset.yml](.github/workflows/docset.yml) for more info.
- Get the latest release tag and compare with current version.
- If newer version is available, build HTML document.
- Convert HTML document to docset by [doc2dash](https://github.com/hynek/doc2dash).

This project is inspired by [roberth-k/dash-docset-aws-cli: AWS-CLI.docset for Dash](https://github.com/roberth-k/dash-docset-aws-cli) that automatically generates docset for AWS-CLI.

Japanese article about this project: [Dash for mac 向けに Optuna ドキュメントの docset 変換を自動化してみた - Qiita](https://qiita.com/29Takuya/items/fa5fd255a40abc871239)
