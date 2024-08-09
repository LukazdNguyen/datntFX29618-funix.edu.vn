# Test Calculator
Hello guys, this is my profile
# Student Test Score Analysis

## Mục tiêu

Dự án này phân tích điểm số của học sinh từ một file văn bản chứa dữ liệu điểm thi. Nó thực hiện các chức năng sau:
- Đọc dữ liệu từ file.
- Kiểm tra tính hợp lệ của dữ liệu.
- Tính điểm cho từng học sinh dựa trên đáp án đúng và sai.
- Tạo báo cáo thống kê và lưu điểm số vào một file kết quả mới.

## Yêu cầu

- Python 3.x
- Thư viện `statistics` (có sẵn trong Python)

## Cấu trúc Dự án

- `analyze_file(file_name)`:
  - Phân tích file dữ liệu điểm thi của học sinh.
  - Tính toán điểm số, tỷ lệ câu hỏi bị bỏ qua và sai.
  - Tạo báo cáo thống kê và lưu kết quả vào một file mới.

## Cách Sử Dụng

1. **Chuẩn bị Dữ Liệu**:
   - Đảm bảo file dữ liệu của bạn có định dạng đúng: mỗi dòng nên có 26 giá trị (mã số học sinh và 25 câu trả lời).
   - Ví dụ dữ liệu: `N000000001,B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D`.

2. **Chạy Chương Trình**:
   - Tạo một file Python (ví dụ: `analyze_scores.py`) và dán mã nguồn vào đó.
   - Chạy chương trình bằng cách sử dụng lệnh:
     ```bash
     python analyze_scores.py
     ```
   - Nhập tên lớp khi được yêu cầu (ví dụ: `class1` cho `class1.txt`).

3. **Kết quả**:
   - Chương trình sẽ in ra báo cáo thống kê trên màn hình.
   - Điểm số của từng học sinh sẽ được lưu vào một file mới có tên `<tên_file_gốc>_grades.txt`.

## Ví dụ

Giả sử bạn có một file dữ liệu `class1.txt` với nội dung:

N000000001,B,A,D,D,C,B,D,A,C,C,D,B,A,B,A,C,B,D,A,C,A,A,B,D,D
N000000002,C,A,D,D,C,A,D,A,C,C,D,A,A,B,A,C,B,D,A,C,A,A,B,D,D
...

Khi chạy chương trình và nhập `class1`, bạn sẽ nhận được một báo cáo thống kê và một file kết quả `class1_grades.txt` với nội dung:

N000000001, 10
N000000002, 8
...


## Ghi chú

- Đảm bảo dữ liệu đầu vào có định dạng đúng để tránh lỗi phân tích.
- Các câu hỏi bị bỏ qua và trả lời sai sẽ được tính và báo cáo trong báo cáo thống kê.

## Liên hệ

Nếu bạn có bất kỳ câu hỏi nào hoặc cần hỗ trợ thêm, vui lòng liên hệ với tôi qua email hoặc qua kênh liên lạc đã được cung cấp.
