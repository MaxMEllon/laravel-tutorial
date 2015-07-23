# laravel-tutorial

larabel練習用repository

## run server
```bash
$ ./artisan serve --host 0.0.0.0
```

## storage
```
$ chmod -R 777 storage
```

## mysql
```
$ sudo service mysqld start
$ mysql -u [user_name]
mysql> create database [database_name] character set utf8;
mysql> create user maxmellon;
mysql> grant insert on `demo_blog`.* to maxmellon@localhost;
mysql> grant select on `demo_blog`.* to maxmellon@localhost;
mysql> grant create on `demo_blog`.* to maxmellon@localhost;
mysql> grant drop on `demo_blog`.* to maxmellon@localhost;
```

## migration
```
$ ./artisan make:migration create_[table_name]s_table
```

## migrate
```
$ ./artisan migrate
```


## Quotation

[Laravel5でシンプルなCRUDアプリを開発する](http://blog.asial.co.jp/1360)

### Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)


### License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
