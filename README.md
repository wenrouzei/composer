# composer

## composer忽略平台以及扩展依赖强制安装
`composer install --ignore-platform-reqs`
`composer update --ignore-platform-reqs`


## composer使用```--memory-limit```限制内存
`composer`安装包报错 `Fatal error: Allowed memory size of 1610612736 bytes exhausted`

更改限制内存大小：

`composer install --memory-limit 2048M`

## composer使用```-1```不限内存
`composer install --memory-limit -1`
