##

[Fargate+RDS(MySQL5.7)+FlaskをCFnで構築してみる](https://dev.classmethod.jp/cloud/aws/flask-rds-fargate-codepipeline1/)

[https://dev.classmethod.jp/cloud/aws/cfn-github-fargate-codepipeline/](https://dev.classmethod.jp/cloud/aws/cfn-github-fargate-codepipeline/)

envfileを作成して以下のように環境変数を記載します。

```bash
# Environment
export CFN_ENV="dev"
```