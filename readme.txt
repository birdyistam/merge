Khởi tạo dự án merge
Thêm cấu hình git
Lưu file
Thêm file vào stage
    - Trước khi thêm file vào stage: untracked - git không quan tâm dù có thao tác gì trên file đi nữa, 
    vì không nằm trong danh sách theo dõi của git
    - Sau khi thêm file vào stage: index added - git đánh chỉ mục (index) các nội dung mới, mới cập nhật 
    trong thư mục làm việc
Commit với messages
    Lúc này git sẽ tạo bản snapshot ghi lại những thay đổi của file
    File hiện tại đang nằm ở local-repository
Publish branch để đẩy những thay đổi lên remote-repository (github)

Từ nhánh main Tâm checkout sang nhánh Tâm
Tâm tạo feature A
    file đang ở trạng thái modified - git check Tâm đang sửa trên cái file readme.txt
Thêm file vào stage: 
    file có trạng thái index modified - git đánh chỉ mục (index) các nội dung đã chỉnh sửa, 
    mới cập nhật trong thư mục làm việc
Commit với messages
Publish branch lên remote