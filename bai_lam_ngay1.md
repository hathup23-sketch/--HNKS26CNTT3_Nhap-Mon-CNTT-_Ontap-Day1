# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:Phạm Thị Thu Hà
- **Lớp:cntt3
- **Link repository:**
- **Hệ điều hành (Windows/macOS):Windown

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

1.Pwd
2.ls -Force
3. mv '.\lich Hoc.txt' docs
 mv .\logo_trung_tam.png,.\anh_lop_hoc.jpg .\media\
4. cp .\media\logo_trung_tam.png .\archive\
5. rm .\temp_201.tmp
   rm .\temp_202.tmp
6.cd .\logs
  Ls
7. cd docs 
   cp ../media/anh_lop_hoc.jpg ../archive/
   cd ..
8. Get-ChildItem -Recurse -Force


```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

```

### Kết quả B1 (pwd)


Path
----
C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh
```text


```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```tex

    Directory: C:\Users\DELL\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh


    
    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/21/2026   9:32 AM                archive
d-----        10/21/2026   9:32 AM                data
d-----        10/21/2026   9:32 AM                docs
d-----        10/21/2026   9:32 AM                logs
d-----        10/21/2026   9:32 AM                media
------        10/19/2026  10:04 AM             83 .env

PS C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh> ls .\docs -Force


    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM             67 lich_hoc.txt


PS C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh> ls .\media -Force


    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
------        10/19/2026  10:04 AM           5184 logo_trung_tam.png


PS C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh> ls .\data -Force


    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM           5070 hoc_vien_khoa_3.xlsx
 Directory: C:\starter-kit\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a----        10/19/2026  10:04 AM           5184 logo_trung_tam.png


    Directory: C:\starter-kit\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 hoc_vien_khoa_3.xlsx

    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM             67 lich_hoc.txt


    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM           1072 access.log
------        10/19/2026  10:04 AM            876 payment.log


    Directory: C:\Users\DELL\Downloads\starter-kit(1)\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
------        10/19/2026  10:04 AM           5184 logo_trung_tam.png



  ## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
