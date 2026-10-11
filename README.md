# saleslens-releases

Kênh phát hành (GitHub Releases) cho tính năng tự cập nhật của ứng dụng desktop "Sales Lens".

Ứng dụng kiểm tra bản mới qua GitHub Releases API, so sánh tag version với version hiện tại, tải asset `SalesLens-Setup-{version}.exe` và xác minh SHA-256 qua file `SHA256SUMS.txt` trước khi cài đặt.
