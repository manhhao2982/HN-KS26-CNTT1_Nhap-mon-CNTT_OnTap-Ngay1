# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Tô Mạnh Hào
- **Lớp:**CNTT1
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
B1 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> dir -force
B2 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> mv .\lich_hoc.txt .\docs\
B3 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> mv .\anh_lop_hoc.JPG,.\logo_trung_tam.PNG .\media\
B4 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> cp .\media\logo_trung_tam.PNG .\archive\
B5 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> rm .\temp_201.tmp
B5 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> rm .\temp_202.tmp
B6 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> cd .\logs\
B6 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\logs> dir
B6 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\logs> cd ..
B7 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> cd .\docs\
B7 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\docs> cp ..\media\anh_lop_hoc.JPG ..\archive\
B8 PS C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh> dir -r


```

### Kết quả B1 (pwd)

```text
Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026  10:29 AM                archive
d-----        10/20/2026  10:32 AM                data
d-----        10/20/2026  10:28 AM                docs
d-----        10/20/2026  10:32 AM                logs
d-----        10/20/2026  10:28 AM                media
-a----        10/20/2026  10:16 AM             83 .env
-a----        10/20/2026  10:16 AM          13559 anh_lop_hoc.JPG
-a----        10/20/2026  10:02 AM            902 bai_lam_ngay1.md
-a----        10/20/2026  10:16 AM             67 lich_hoc.txt
-a----        10/20/2026  10:16 AM           5184 logo_trung_tam.PNG
-a----        10/20/2026  10:16 AM             22 temp_201.tmp
-a----        10/20/2026  10:16 AM             22 temp_202.tmp


```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026  11:24 AM                archive
d-----        10/20/2026  10:32 AM                data
d-----        10/20/2026  10:40 AM                docs
d-----        10/20/2026  10:32 AM                logs
d-----        10/20/2026  10:44 AM                media
-a----        10/20/2026  10:16 AM             83 .env
-a----        10/20/2026  10:02 AM            902 bai_lam_ngay1.md


    Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:16 AM          13559 anh_lop_hoc.JPG
-a----        10/20/2026  10:16 AM           5184 logo_trung_tam.PNG


    Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:16 AM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:16 AM             67 lich_hoc.txt


    Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:16 AM           1072 access.log


    Directory: C:\Users\Manh Hao\Downloads\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026  10:16 AM          13559 anh_lop_hoc.JPG
-a----        10/20/2026  10:16 AM           5184 logo_trung_tam.PNG


```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
