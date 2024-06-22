Mã nguồn cho Hệ thống thu thập dữ liệu PIR Array
========

Link tới các mã nguồn:
---------

File báo cáo: https://github.com/Mungnv212894/Bao_cao_do_an_1/blob/main/BAO_CAO.pdf

Source code cho ESP32: [https://github.com/sonnt0201/main/tree/dual-core]()

Source code của Backend Server: [https://github.com/sonnt0201/pirserver_linux]()

Source code của ứng dụng giao diện: [https://github.com/sonnt0201/pirmanager]()


Tổng quan:
------

Mục tiêu của dữ án là giải quyết vấn đề về việc thu thập, lưu trữ, cung cấp và gán nhãn dữ liệu từ PIR Array. Dự án bao gồm:

- Mạch cứng PIR Array gồm 5 PIR trả về các giá trị ADC từ 0 đến 4095.

- Phần mềm để thu thập lưu trữ và cung cấp các dữ liệu PIR đã ghi được, cung cấp công cụ để quay video hiện trường thử nghiệm cũng như để gán nhãn cho dữ liệu đã có.

(Chi tiết xem tại `Báo cáo dự án` được gửi kèm)

Phần mềm cho Hệ thống thu thập dữ liệu PIR Array bao gồm 3 phần chính:

- Mã nguồn cho vi điều khiển ESP32
- Mã nguồn cho Backend Server - Pirserver_linux
- Mã nguồn cho ứng dụng Desktop - Pir Manager.

Các môi trường cho mã nguồn:
-----

### Mã nguồn của ESP32:

- Môi trường: ESP-IDF.
- Ngôn ngữ: C lang.
- Hệ điều hành: Window, Linux, Mac

### Mã nguồn của Pirserver_linux:

- Hệ điều hành: Linux (Debian-based system).
- Ngôn ngữ : C++.
- Build tool: CMake.
- Các thư viện chính được sử dụng: Sqlite, JsonCPP.

### Mã nguồn của phần mềm giao diện Pir Manager

- Môi trường: NodeJS.
- Ngôn ngữ: TypeScript.
- Các thư viện chính sử dụng: ElectronJS, ReactJS, TailwindCSS, ...
- Hệ điều hành: Window, Linux, Mac.

**Click vào link các mã nguồn để xem chi tiết**

-------

**2024 by Thai-Son Nguyen.**

🧑‍💻🧑‍💻🧑‍💻 Happy coding 🧑‍💻🧑‍💻🧑‍💻
