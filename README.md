# JEP 378 – Text Blocks (Java 15)

### Mục tiêu
JEP 378 giúp lập trình viên viết chuỗi nhiều dòng (`multiline strings`) dễ hơn, rõ ràng hơn, và hạn chế lỗi khi xử lý ký tự đặc biệt.

### Cú pháp
Dùng ba dấu nháy kép `"""` để mở và đóng chuỗi văn bản nhiều dòng.

### Ví dụ
```java
String html = """
    <html>
        <body>
            <h1>Hello, Java 15!</h1>
            <p>Đây là ví dụ minh họa cho JEP 378 - Text Blocks.</p>
        </body>
    </html>
    """;
System.out.println(html);
