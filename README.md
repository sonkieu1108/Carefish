# Điều khiển đèn, bơm nước và servo bằng ESP8266 và Blynk

Dự án này là code Arduino cho ESP8266 để điều khiển đèn, bơm nước và servo thông qua ứng dụng Blynk.

## Linh kiện

* ESP8266 (ví dụ: NodeMCU)
* Relay (2 kênh)
* Servo SG90
* Nút nhấn
* Dây nối

## Sơ đồ kết nối

* Relay 1 (đèn) -> ESP8266 D1
* Relay 2 (bơm nước) -> ESP8266 D3
* Nút nhấn -> ESP8266 D2
* Servo SG90 -> ESP8266 D5

## Chức năng

* Điều khiển đèn và bơm nước bằng relay thông qua ứng dụng Blynk.
* Điều khiển servo từ ứng dụng Blynk.
* Điều khiển đèn bằng nút nhấn vật lý.

## Hướng dẫn sử dụng

1.  Kết nối các linh kiện theo sơ đồ.
2.  Cài đặt thư viện Blynk và Servo trong Arduino IDE.
3.  Nạp code lên ESP8266.
4.  Cài đặt ứng dụng Blynk trên điện thoại và tạo project với các widget tương ứng.
5.  Nhập thông tin Blynk và WiFi vào code.
6.  Sử dụng ứng dụng Blynk để điều khiển đèn, bơm nước và servo.
