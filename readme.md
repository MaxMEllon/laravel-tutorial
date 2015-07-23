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
$ sudo mysql  # database user をrootにした時．
mysql -> create database [database_name]
```

## migration
```
$ ./artisan make:migration create_[table_name]s_table
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
