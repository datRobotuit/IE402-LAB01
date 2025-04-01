# IE402-LAB01
LAB01 402.P21 Thông Tin Địa Lý 3 Chiều - NHÓM 07

## Cây thư mục:
  - **images**: thư mục ảnh, chủ yếu chứa icon cho các loại điểm trên bản đồ (thị xã, thành phố, cầu)
  - **point**: chứa dữ liệu JSON các điểm
    + bridges.json: các điểm cầu đường bộ
    + cities.json: các điểm thành phố
    + towns.json: các điểm thị xã
  - **polygon**: chứa dữ liệu JSON các đa giác tỉnh và cung đường bộ
    + provinces: thư mục đa giác tỉnh
      * an_giang.json, bac_lieu.json, ben_tre.json,... <ten_tinh>.json: dữ liệu (tên, tọa độ, diện tích, dân số) của mỗi tỉnh
      * _index.json_: file index chứa tên của các file JSON tỉnh để nạp vào script.js
    + roads: thư mục cung đường bộ
      * ql61.json, ql61b.json,... <ten_duong>.json: dữ liệu (tập hợp các điểm tạo nên cung) của mỗi đường
      * _index.json_: file index chứa tên của các file JSON đường để nạp vào script.js
  - **screenshots**: ảnh chụp màn hình demo
  - **index.html**: HTML chính
  - **styles.css**: CSS
  - **script.js**: JavaScript, file tương tác chính tới ESRI ArcGIS JavaScript API

## Cách thêm dữ liệu:
- **Với các điểm**: Thêm trực tiếp vào các file _bridges.json, cities.json, towns.json_   
- **Với các đa giác, cung**: Tạo file mới, thêm dữ liệu vào, sau đó điền tên file mới tạo vào _index.json_

## Deploy:
Có thể deploy cục bộ trên máy cá nhân, chạy trực tiếp từ file index.html hay dùng extension Live Server từ VS Code IDE

## Screenshot:
![View 2D mặc định](/screenshots/2d_view.png "View 2D mặc định")
![View 2D màu đơn giản](/screenshots/2d_view_simple_color.png "View 2D màu đơn giản")
![View 2D với basemap khác](/screenshots/2d_view_different_basemap.png "View 2D với basemap khác")
![View 3D](/screenshots/3d_view.png "View 3D")
