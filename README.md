# FKhởi tạo ứng dụng Flutter đầu tiên

Bước đầu làm quen với Flutter hãy bắt đầu với bằng khởi tạo ứng dụng Flutter đầu tiên.

<img src="https://teamvietdev.com/wp-content/uploads/2018/11/teamvietdev-flutter-logo.jpg" alt="Khởi tạo ứng dụng Flutter đầu tiên">

Tạo một ứng dụng Flutter đơn giản và khởi chạy với ứng dụng Flutter đầu tiên của bạn. Bạn hãy khởi động Android Studio lên, chọn mục File > New Flutter Project.

<img src="https://teamvietdev.com/wp-content/uploads/2018/11/teamvietdev-khoi-tao-ung-dung-flutter-dau-tien-h1.jpg" alt="Khởi tạo ứng dụng Flutter đầu tiên">

Sau đó chọn mục Flutter application làm loại dự án và nhấn Next.

<img src="https://teamvietdev.com/wp-content/uploads/2018/11/teamvietdev-khoi-tao-ung-dung-flutter-dau-tien-h2.jpg" alt="Khởi tạo ứng dụng Flutter đầu tiên">

Nhập tên dự án chẳng hạn flutter_hello_world và nhấn Next để qua bước kế tiếp.

<img src="https://teamvietdev.com/wp-content/uploads/2018/11/teamvietdev-khoi-tao-ung-dung-flutter-dau-tien-h3.jpg" alt="Khởi tạo ứng dụng Flutter đầu tiên">

Tiếp theo bạn khai báo thêm thông tin Company domain và Package name rồi nhấn Finish để hoàn thành khởi tạo chương trình Flutter đầu tiên.

<img src="https://teamvietdev.com/wp-content/uploads/2018/11/teamvietdev-khoi-tao-ung-dung-flutter-dau-tien-h4.jpg" alt="Khởi tạo ứng dụng Flutter đầu tiên">


Mã nguồn <a href="https://teamvietdev.com/khoi-tao-ung-dung-flutter-dau-tien/">khởi tạo ứng dụng Flutter đầu tiên</a>:

```
import 'package:flutter/material.dart';
 
void main() => runApp(MyApp());
 
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Welcome to Flutter',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Welcome to Flutter'),
        ),
        body: Center(
          child: Text('Hello World'),
        ),
      ),
    );
  }
}
```

Tìm hiểu thêm về <a href="https://teamvietdev.com/chuyen-muc/flutter/">Flutter</a> tại 
<a href="https://teamvietdev.com/">Team Việt Dev</a>.
