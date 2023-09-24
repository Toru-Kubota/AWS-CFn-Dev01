# S3静的WEBホスティング
## 構成
* S3の静的WEBホスティング機能でWEBサイト構築
* アクセスログをログバケットに取得

![sc-cfn-dev01](https://github.com/Toru-Kubota/AWS-CFn-Dev01/assets/102895466/a1fe1711-73c3-4e3a-ae4b-0e7c0e559bb8)

## パラメーター
### 01_01_S3-log.yaml
* Prefix: Log Bucket名
### 01_02_S3-web.yaml
* Prefix: Web Bucket名
* S3AllowedIP: 許可するグローバルIP
