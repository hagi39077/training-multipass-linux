# training-multipass-linux

## setup

`multipass launch 22.04 --name training-multipass-linux`  
`multipass shell training-multipass-linux`

## Shutting Down and Deleting Virtual Environment Instances

`exit`  
`multipass stop training-multipass-linux`  
`multipass delete training-multipass-linux`  
`multipass purge`  
`multipass ls`

## command list

`multipass find` 利用可能な Ubuntu のバージョンを確認する  
`multipass launch <version> --name <name>	`Ubuntu のバージョン <version> を <name> という名前の VM インスタンスとして作成・起動する  
`multipass start <name>	`既に存在する <name> という名前のインスタンスを起動する  
`multipass shell <name>	<name>` という名前の VM インスタンスのシェルにログインする  
`multipass ls	VM` インスタンスの一覧を見る  
`multipass stop <name> <name> `という名前の VM インスタンスを終了する  
`multipass delete <name>	<name> `という名前の VM インスタンスを削除する  
`multipass purge` 過去に起動した VM インスタンスを永久に削除する
