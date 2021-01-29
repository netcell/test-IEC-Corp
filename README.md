# test-IEC-Corp
chú thích mục (1) đã hoàn thành
chú thích mục (2) 
tạo 1 button tăng score trong shop gọi đến method CheatScore() trong class ShopUI, khi tăng tiền thì người chơi có thể mua vật phẩm 1 cách tự do nên em sẽ k làm cheat tăng từng vật phẩm nữa
chú thích mục (3) cái này dễ mà em lười không muốn làm.
Chú thích mục (4) cái này dễ mà em lười không muốn làm.
Chú thích mục (5) việc thay nhân vật có liên quan đến addressable asset system, đây là 1 kiến thức mới đối với em, em cần thời gian tìm hiểu nên chưa thực hiện trong thời gian bài test được.
Chú thích mục (6) 
em đã thực hiện công việc này đối với sản phẩn army tanker multiplayer online battle arena của em nhưng với Database em sử dụng là playfab, nên em nghĩ việc tích hợp sử dụng firebase và lưu trữ data trên đó cũng sẽ có nhiều thứ tương đồng và cũng k phải là một vấn đề quá khó ạ.
chú thích mục (7) 
-   Cải tiến hiệu năng game bằng cách giảm Batches và SetPass calls bằng cách Pack Sprite hoặc dùng Atlas Packer đối với 2D, còn đối với các vật thể 3D thì các đỉnh tối đa của các model <= 1000 và sử dụng kỹ thuật combineMesh => giảm công việc cho GPU
Cải tiến code bằng cách tránh khai báo biến và khởi tạo biến không đúng cách để giảm tối thiểu việc phân cấp bộ nhớ cho các biến
Dùng Kỹ thuật Pooling giảm thiểu công việc của trình garbage collection (GC) => giảm công việc cho CPU
-   về tổ chức foler hiện tại việc khi thêm các plugin bên thứ 3 của unity vào project thì sẽ sinh ra thêm nhiều folder dẫn đến sẽ có làm sự xáo trộn giữa các thu mục plugin và các thư mục do mình tạo ra => khó khăn trong việc đọc dự án với người mới, và khi project lơn lên thì việc quản lý những tài nguyên hiện tại sẽ khó khăn hơn
đề xuất tạo 1 thư mục GameDeveloper chưa tất cả các thư mục mà do chính nhà phát triển tạo ra như sprite, scripts, audio, animation....
với những big project thì cần quản lý bằng các tool Version control system như git, sử dụng git flow để quản lý source 1 cách tốt nhất khi dự án có nhiều developer.
