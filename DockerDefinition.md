# KHÁI NIỆM CƠ BẢN TRONG DOCKER

## DOCKER LÀ GÌ ?

### OS-LEVEL VIRTUALIZATION 

- Công nghệ ảo hóa dựa vào hệ điều hành.
- Ưu điểm :
  - Linh hoạt : quản lí và phân chia tài nguyên hiệu quả hơn .
  - Tiết kiệm tài nguyên hệ thống : Tránh lãng phí tài nguyên hệ thống(CPU, RAM, Storage) cho hypvisor và hệ điều hành.
  - Hiệu Năng:
- Nhược điểm :
  - Kém ổn định nếu không được quản lí hợp lí .

### VIRTUAL MACHINE 

- Công nghệ ảo hóa dựa vào phần cứng Hardware-Level Virtualization.


### LXC (LINUX CONTAINER)

- Là giải pháp ảo hóa cho phép nhiều hệ thống Linũ cùng hoạt động trên một máy chủ vật lý, sử dụng chung Linux Kernel.

## IMAGE

- Image là một template được đóng gói sẵn vf không đổi trong toàn bộ quá trình chạy container( Trừ khi build lại image). Giống như trong OOP, image là class còn container là object của class đó.
- Ta có thể tự build image cho riêng mình hoặc dowload các image có sẵn từ Dochub.

## CONTAINER

- Container được khởi chạy từ các image, .bên tỏng sẽ có đầy đủ các ứng dụng cần thiết mà bạn định nghĩa từ Image.

## DOCKER REGISTRY

- là kho chứa các image.
- Ta có thể dựng nên một Doker Registry cho riêng mình.
