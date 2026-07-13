"""
Bài 1
- Python là một trong những ngôn ngữ thông dịch phổ biến nhất
- vì:
+ Chạy mã ừng dòng một. Có nghĩa lệnh được thực thi mà không cần biên dịch toàn bộ chương trình thành ngôn ngữ máy trước đó.
Bài 2
2.1 các kiểu dữ liệu trong python
+ xâu kí tự (str)
+ số nghuyên (int)->Số không có phần thập phân (ví dụ: 10, -5).
+ số thực (float)->Số có dấu phẩy động, chứa phần thập phân (ví dụ: 3.14, 1.0).
+ kiểu logic (bool )->  Chỉ có hai giá trị True (Đúng) hoặc False (Sai).
2.2 các toán tử trong python
toán tử số học
   + : Cộng
   - : Trừ
   * : Nhân
   / : Chia lấy số thực (Ví dụ: 7 / 2 = 3.5)
   // : Chia lấy phần nguyên, làm tròn xuống (Ví dụ: 7 // 2 = 3)% : Chia lấy phần dư (Ví dụ: 7 % 2 = 1)
   ** : Lũy thừa (Ví dụ: 2 ** 3 = 8) 
toán tử so sánh
    == : Bằng nhau
    != : Khác nhau
    > : Lớn hơn
    < : Nhỏ hơn
    >= : Lớn hơn hoặc bằng
    <= : Nhỏ hơn hoặc bằng
toán tử logic
    and : Trả về True nếu tất cả các điều kiện đều đúng.
    or : Trả về True nếu có ít nhất một điều kiện đúng.
    not : Phủ định điều kiện, đảo ngược True thành False và ngược lại.
toán tử gán
    = : Gán giá trị thông thường (Ví dụ: x = 5)
    += : Cộng rồi gán (Ví dụ: x += 3 tương đương x = x + 3)
    -= : Trừ rồi gán
    *= : Nhân rồi gán
    /= : Chia rồi gán
mệnh đề điều kiện và vòng lặp
- Mệnh đề điều kiện (if  elif - else) =>Dùng để kiểm tra điều kiện và thực hiện các lệnh tương ứng.
if điều_kiện:
    # khối lệnh
elif điều_kiện:
    # khối lệnh
else:
    # khối lệnh
- Vòng lặp for=>Dùng khi biết trước số lần lặp hoặc lặp qua các phần tử.
for biến in dãy:
    # khối lệnh
- Vòng lặp while=>Dùng khi lặp đến khi điều kiện sai.
while điều_kiện:
    # khối lệnh
- break và continue
break: Dừng vòng lặp ngay lập tức.
continue: Bỏ qua lần lặp hiện tại và chuyển sang lần lặp tiếp theo.
2.4 Kiểu dữ liệu true, false
Kiểu dữ liệu Boolean (bool) chỉ có 2 giá trị:
True : Đúng
False : Sai
Boolean thường được dùng trong điều kiện (if) và vòng lặp (while).
"""