```shell
特定のファイルのみアップロード
% aws s3 cp index.html s3://${bucketname}

全てのファイルをアップロード
% aws s3 cp . s3://akiraishii.work --recursive
```
