1. Cài thư viện OpenCV và Pillow
pip install opencv-python
pip install pillow
2. Đọc và hiển thị ảnh
Mục tiêu: Đọc một hình ảnh từ máy tính, hiển thị lên màn hình và lưu lại với định dạng khác.
Các bước sau:
-   Đọc một file ảnh bằng OpenCV và Pillow(.jpg).
-   Hiển thị lại ảnh trong file đã đọc.
-   Lưu ảnh sang định dạng khác (.jpg -> .png)
3. Chuyển đổi không gian màu
Mục tiêu: Chuyển đổi ảnh sang không gian màu khác
Các bước sau: (cvtColor của OpenCV và convert của Pillow)
-   Chuyển ảnh từ RGB sang Grayscale.
-   Chuyển ảnh sang không gian màu HSV và LAB (OpenCV sẽ hỗ trợ cái này tốt hơn).
4.  Cắt xén và thay đổi kích thước ảnh
Mục tiêu: Thao tác với kích thước và vùng hiển thị ảnh.
Các bước sau:
-   Cắt một vùng hình ảnh bất kỳ (crop)
-   Thay đổi kích thước:
    +   Sử dụng OpenCV:
    -   Thay đổi kích thước theo tỷ lệ hoặc kích thước cố định (resize).
    +   Sử dụng Pillow:
    -   Thay đổi kích thước cố định (resize).
    -   Thay đổi theo tỷ lệ, giữ nguyên tỉ lệ khung hình (thumbnail).
5.  Vẽ hình và thêm nội dung văn bản vào ảnh
Mục tiêu: Vẽ các hình ảnh cơ bản và thêm văn bản lên ảnh.
Các bước sau:
-   Vẽ đường thẳng lên ảnh (line).
-   Vẽ hình tròn lên ảnh (circle của OpenCV hoặc ellipse của Pillow).
-   Vẽ hình chữ nhật lên ảnh (rectangle)
-   Thêm văn bản vào ảnh (putText của OpenCV và text của Pillow)