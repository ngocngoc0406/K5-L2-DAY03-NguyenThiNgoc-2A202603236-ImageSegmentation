# Báo cáo thực hành Day 3

- Mã học viên theo lớp: 2A202603236
- Họ và tên: Nguyễn Thị Ngọc
- Ngày / CVAT local: 12/11/2026 / CVAT local
- Công cụ đã dùng: CVAT local.

## 1. Bài đã nộp

| Task | File ZIP đúng tên | Hoàn thành mấy ảnh |
| --- | --- | ---: |
| easy_semantic | `easy_semantic.zip` | 3 / 3 |
| medium_instance | `medium_instance.zip` | 3 / 3 |
| hard_panoptic | `hard_panoptic.zip` | 2 / 2 |
| cp1_holes | `cp1_holes.zip` | 1 / 1 |
| cp2_slice | `cp2_slice.zip` | 1 / 1 |
| cp5_occlusion | `cp5_occlusion.zip` | 1 / 1 |
| cp3_thin | `cp3_thin.zip` | 1 / 1 |
| cp4_curb | `cp4_curb.zip` | 1 / 1 |
| cp6_coverage | `cp6_coverage.zip` | 1 / 1 |

## 2. Một quyết định trước khi dùng gợi ý

Chưa nhớ object Medium đầu tiên, class/quy tắc biên hoặc có dùng gợi ý AI hay không.

## 3. Lỗi phát hiện

Tự kiểm cho thấy annotation Medium cần được xem lại; chưa xác định mask cụ thể và chưa sửa trong CVAT.

## 4. Các ca chưa chắc

| Ảnh/vị trí | Hai cách hiểu có thể | Quy tắc/chứng cứ | Quyết định hoặc câu hỏi cho coach |
| --- | --- | --- | --- |
| Hard panoptic (chưa nhớ tên ảnh/vị trí) | Xe bị mờ; khó xác định class hoặc ranh của phần nhìn thấy. | Cần xem lại ảnh gốc và chỉ gán phần có thể nhận diện. | Hỏi coach cách xử lý vùng xe mờ này. |
| Hard panoptic (chưa nhớ tên ảnh/vị trí) | Khoảng trống trong tán cây có thể là nền nhìn xuyên qua hoặc vùng cây bị bỏ sót. | Phân biệt phần vegetation nhìn thấy với nền phía sau. | Hỏi coach khoảng trống cụ thể này nên để nền hay gán vegetation. |
