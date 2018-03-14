# Package name

## Intro

Giới thiệu qua về package

## Requirements

Những yêu cầu khi dùng package

## Usage

Cách sử dụng, có thể được hoàn thiện bởi người dev

## Test

Hướng dẫn người dev cách test

## Other information 

Thông tin khác nếu có. Viết dạng heading sau đó ghi chi tiết

### PHPUNIT config generate

```
#$ ./vendor/bin/phpunit --generate-configuration 
PHPUnit 7.0.2 by Sebastian Bergmann and contributors.

Generating phpunit.xml in /Users/hocvt/Documents/webroot/kw_system/packages/base

Bootstrap script (relative to path shown above; default: vendor/autoload.php): 
Tests directory (relative to path shown above; default: tests): 
Source directory (relative to path shown above; default: src): 

Generated phpunit.xml in /Users/hocvt/Documents/webroot/kw_system/packages/base
```

### PHPUNIT extensions

Có một số project cần test với tool đặc thù riêng thì xem thêm [danh sách extensions](https://phpunit.de/extensions.html)