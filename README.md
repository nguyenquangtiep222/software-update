# ------------------ HƯỚNG DẪN ĐỌC FILE ------------------

# DÒNG ĐẦU TIÊN (DUY NHẤT): THÔNG TIN UPDATE PHẦN MỀM
# Cú pháp: update|<link download>|<version>
# - <link download>: Đường link tải về phiên bản mới nhất.
# - <version>: Phiên bản mới nhất và ngày phát hành.

update|https://drive.google.com/file/d/...|v1.0.0 (08/08/2025)


# ------------------ CÁC DÒNG SAU: DANH SÁCH KEY KÍCH HOẠT ------------------

# Cú pháp: key<sha256>|<loại phiên bản>|<ngày hết hạn>|<SĐT hoặc MST>|<trạng thái>|<ghi chú>
# - <sha256>: Mã hóa SHA256 từ serial phần cứng máy tính (ổ cứng).
# - <loại phiên bản>: 'v' = VIP (đầy đủ tính năng), 'l' = Limited (bị giới hạn).
# - <ngày hết hạn>: Dạng dd/MM/yyyy. Tool không hoạt động sau ngày này.
# - <SĐT hoặc MST>: Số điện thoại hoặc MST để quản lý người dùng.
# - <trạng thái>: 'o' hoặc bỏ trống. Không ảnh hưởng.
# - <ghi chú>: Tùy ý nội bộ: tên người, máy, ngày cài,...

key979ebe1c79e9ad87611c94dec6395|v|01/01/2030|0902965789|o|ngày cài: 01/01/2025
keyabcd1234cba9876abcd1234cba9876|l|01/01/2030|0941891456|o|ngày cài: 01/01/2025


# ------------------ KẾT THÚC FILE ------------------
