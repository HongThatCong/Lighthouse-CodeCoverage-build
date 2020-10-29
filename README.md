# lighthouse-CodeCoverage-build

Lighthouse CodeCoverage PinTool build.

Build with Lighhouse code v0.9.1 và Pin Kit mới nhất hiện tại của Intel: Pin-3.16.98275

# Intro
Lighthouse là 1 IDA plugin, chuyên về code Coverage. Được sử dụng rất nhiều và được đánh giá là 1 trong những plugin tốt nhất, nổi tiếng nhất.

Mấy anh "tìm gián, đục lỗ" hay dùng plugin này.

CodeCoverage.dll là CodeCoverage64.dll là 2 PinTool được Lighthouse dùng để create/import log tracer từ Pin vào Lighthouse.

# HDSD

Đọc kỹ hdsd tại: 

https://github.com/gaasedelen/lighthouse

# HD Install:

Nên chép 2 dll CodeCoverage.dll và CodeCoverage64.dll vào chung thư mục của Pin.exe (thư mục %PIN_ROOT%)

# HD Build:

Sau này các bạn có thể tự build CodeCoveragexx.dll với Pin mới, 

Yêu cầu: đã install VS20xx và Pin

1. Vào 2 file build-x86.bat và build-x64.bat, sửa lệnh call vcvarsall.bat lại cho đúng path trên máy các bạn

2. Định nghĩa biến môi trường PIN_ROOT cho đúng với thư mục Pin gốc của các bạn

3. cmd, build-x86/x64.bat enter là xong phim :D

Chân chọng, bét xì ga :D
