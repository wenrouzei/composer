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

## `composer require` 命令来安装指定版本的包
例如，如果你想安装 Laravel 5.5 的一个具体版本，可以使用以下命令：

`composer require laravel/framework:5.5.40`

## `composer require` 命令来安装指定版本范围的包
例如，如果你想安装 Laravel 5.5 的任何补丁版本，但不想升级到 5.6 或更高版本，你可以这样指定：

`composer require laravel/framework:^5.5`
