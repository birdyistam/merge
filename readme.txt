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

Tâm đã hoàn thành feature A 
Tâm muốn merge nhánh Tâm vào nhánh main 
Tâm checkout nhánh main 
Tâm merge nhánh Tâm vào nhánh main bằng: git merge Tâm

Tâm chỉ commit dòng 23 24 25 26 vào local-repository của nhánh Tâm
Sau đó merge nhánh Tâm từ local-repository lên nhánh remote-repository của nhánh main
Do đó remote-repository của nhánh Tâm chưa có dòng 23 24 25 26
Nhánh Tâm chưa đồng bộ code
Nhưng Hân lại checkout từ nhánh của Tâm, quên phải checkout từ head mới nhất trên nhánh main
Giờ làm sao ta?
Dùng: git fetch origin?

Hân merge nhánh Hân vào main

