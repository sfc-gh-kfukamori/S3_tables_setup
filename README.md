# S3_tables_setup

# テーブルバケットの作成
S3テーブルバケットは、テーブルとしてS3のリソースとして作成できるために使用できるS3バケットのタイプ。  
S3テーブルの使用を開始するために、まずテーブルバケットを作成する。　　
リージョンとバケット名を指定して作成。

作成するとARNは以下の様な命名規則となる。

arn:aws:s3tables:region:owner-account-id:bucket/bucket-name

