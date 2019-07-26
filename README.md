# shineyork/sjunit-laravel

这里是对于框架的介绍

# 对于框架的 要求

Laravel >= 5.1 & PHP > 7.1.3 

# 安装的方式

```yml
composer require "shineyork/sjunit-laravel"
```

# 配置方式
5.5手动配置laravel对于``ShineYork\SJunitLaravel\Providers\SJunitServiceProvider::class``服务放到config/app.php中

解释路由
```php
<?php
Route::get('/', 'SJunitController@index');
Route::post('/', 'SJunitController@store')->name('junit.store');
?>
```
