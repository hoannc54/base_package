**Tài liệu được tạo ra để lưu hành và đào tạo nội bộ, 
anh em coder đi qua có ý kiến đóng góp vui lòng viết issue hoặc liên hệ trực tiếp**

## Base composer package for package development

- [Sample readme](sample_readme.md) rename file này thành file readme.md của bạn :)

## Viết test

- Việc viết test có thể sẽ hơi khó khăn cho các bạn mới làm kiểu viết test trước code. 
Do đó có thể khởi tạo một số class base để mường tượng được package của mình sẽ làm gì, 
cho ra cái gì sau đó viết test cho các hàm viết tạm đó(chưa viết code xử lý, chỉ giả lập đầu vào đầu ra).
- Với các trường hợp cần viết test cho 1 đầu ra nào đó bạn phân vân, hãy viết vào issue để được hỗ trợ.
- Viết test không nhất thiết phải sử dụng phpunit, đối với đầu ra kiểm chứng bằng mắt thì nên viết test sao cho 
người dùng thấy được đầu vào đầu ra và mô tả đầu ra kỳ vọng như thế nào.

### Write testing showcases

_test file cho một số trường hợp cụ thể (thêm trường hợp của bạn vào [issue](https://github.com/vuthaihoc/base_package/issues/new) để chia sẻ/trao đổi)_
 

## PHPUNIT config generate

```
#$ ./vendor/bin/phpunit --generate-configuration 
PHPUnit 7.0.2 by Sebastian Bergmann and contributors.

Generating phpunit.xml in /Users/hocvt/Documents/webroot/kw_system/packages/base

Bootstrap script (relative to path shown above; default: vendor/autoload.php): 
Tests directory (relative to path shown above; default: tests): 
Source directory (relative to path shown above; default: src): 

Generated phpunit.xml in /Users/hocvt/Documents/webroot/kw_system/packages/base
```

## PHPUNIT extensions

Có một số project cần test với tool đặc thù riêng thì xem thêm [danh sách extensions](https://phpunit.de/extensions.html)