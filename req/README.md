# Introduction Overview About Requirements

> TODO: Translate to English late
## Tree contents of project
```
|-- 1. Dashboard: Trang tổng quan show overview tất cả mọi thứ sau khi user login vào có thể thấy đc.
    |-- 1.1 Total Features Widget: Show tổng sổ feature sẽ implement của milestone hiện tại (ex: v1.1)
    |-- 1.2 Total Bugs Widget: Show tổng sổ bug của milestone hiện tại (ex: v1.1)
    |-- 1.3 Open Bugs Widget: Show số lượng bug đang open của milestone hiện tại (ex: v1.1)
    |-- 1.4 Close Bugs Widget: Show số lượng bug đã được close của milestone hiện tại (ex: v1.1)
    |-- 1.5 New Feeds Widget: Show 5 feeds mới nhất
    |-- 1.6 Todo List Widget: Show todo list cần làm của user login
    |-- 1.7 Một số loại Chart để xem thống kê, report.
    |-- ???
|-- 2. Feed (Activity): Trang thấy được mọi hoạt động của all users.
    |-- 2.1 Giống như trang home kiểu fb nhưng làm vài tính năng nhỏ bao gồm: user có thể post bài, up ảnh vô chỗ này, show các activities của user lên feed này như chuyển trạng thái của bug, feature...
    |-- 2.2 Thêm phần like đồ nữa thì hấp cmn dẫn. Và mỗi cái feed sẽ có 1 cái link qua page riêng để view detail kiểu như slack, user có thể copy link này bỏ vào description của issue hoặc để share cho người khác.
|-- 3. Issues
    |-- 3.1 Datatables show tất cả cái bug, feature
    |-- 3.2 Filter
|-- 4. Milestones
    |-- 4.1 Show tất cả các version hoặc quá trình đã và đang chạy của project và click vào thì thấy được bug và feature của mỗi milestone
|-- 5. Documents
    |-- 5.1 Viết, lưu trữ, hiển thị tất cả thông tin về document setup project, spec, file, report, attachments....
|-- 6. Calendar
    |-- 6.1 Hiển thị calendar và các event quan trọng
|-- 7. Users
    |-- 7.1 Phân quyền, add user, xoá user....
|-- 8. Setting
    |-- 8.1 Thiết lập lung tung như tạo category, status cho issue, show cái này, ẩn cái kia....
|-- 9. Notification
    |-- Bắn notification về cho user nếu đc assign feature, bug hoặc user khác update status issue của user này hoặc remind nhắc nhở gì đó ...
```

*Note*: Phần 1, tuỳ thuộc vào user login. Nếu là user có role như pm, tl... thì sẽ show widget giống như trên. Còn nếu có role như dev, qc chẳng hạn thì chỉ show number của feature, bug được assign...

## User Distribution
```
|-- Adminitrators
|-- Users
```

## Role
```
|-- Project manager
|-- Team leader
|-- Developer
|-- Tester
```