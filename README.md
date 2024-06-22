# README

## Ứng dụng Quản lý Thi Trắc Nghiệm

Ứng dụng này cung cấp các chức năng để quản lý thi trắc nghiệm, bao gồm quản lý môn học, lớp học, sinh viên, điểm thi, câu hỏi thi và các chức năng liên quan đến thi trắc nghiệm. Ứng dụng được tổ chức thành nhiều phần chính, mỗi phần cung cấp các tính năng cụ thể.

## Cấu trúc Dữ liệu

1. **Danh sách Môn học**
    - Danh sách tuyến tính có tối đa 300 môn học.

2. **Danh sách Lớp**
    - Mảng con trỏ có tối đa 500 lớp.

3. **Danh sách Sinh viên**
    - Danh sách liên kết đơn.

4. **Danh sách Điểm thi**
    - Danh sách liên kết đơn.

5. **Danh sách Câu hỏi thi**
    - Cây nhị phân tìm kiếm.
      
## Chức năng của Chương trình

### A. Đăng nhập
- Đăng nhập dựa vào mã sinh viên và password.
- Nếu tài khoản đăng nhập là GV và pass là GV thì sẽ có toàn quyền.

### B. Quản lý Lớp
1. **Nhập Lớp**
    - Thêm, xóa, hiệu chỉnh thông tin các lớp.

2. **In Danh sách Lớp**
    - In danh sách lớp theo một niên khóa.

3. **Nhập Sinh viên vào Lớp**
    - Nhập mã lớp trước, sau đó nhập các sinh viên vào lớp đó.

### C. Quản lý Môn học
1. **Nhập Môn học**
    - Thêm, xóa, hiệu chỉnh thông tin của môn học.

### D. Quản lý Câu hỏi thi
1. **Nhập Câu hỏi thi**
    - Id là số nguyên dương ngẫu nhiên do chương trình tự tạo.

### E. Thi Trắc nghiệm
1. **Thi Trắc nghiệm**
    - Trước khi thi, hỏi người thi môn thi, số câu hỏi thi, số phút thi.
    - Lấy ngẫu nhiên các câu hỏi trong danh sách câu hỏi thi của môn.

2. **In Chi tiết các Câu hỏi đã thi của một Môn học của một Sinh viên**
    - In chi tiết các câu hỏi đã thi của một môn học cho một sinh viên.

3. **In Bảng điểm Thi Trắc nghiệm của một Môn học của một Lớp**
    - Nếu có sinh viên chưa thi thì ghi “Chưa thi”.

---


