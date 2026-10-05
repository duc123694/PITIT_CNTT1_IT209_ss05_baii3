# Bài 3: Xử lý xung đột phức tạp trong quá trình Rebase

## 1. Mục tiêu

Thực hiện rebase nhánh `feature-api` lên nhánh `master`, xử lý các conflict phát sinh trong quá trình rebase và đảm bảo lịch sử Git được sắp xếp theo dạng tuyến tính.

## 2. Các nhánh sử dụng

- Nhánh chính: `master`
- Nhánh tính năng: `feature-api`
- File xảy ra conflict: `Homework/HW-03/config.json`

## 3. Thực hiện Rebase

Sau khi tạo các commit trên hai nhánh, chuyển sang nhánh `feature-api`:

```bash
git checkout feature-api
