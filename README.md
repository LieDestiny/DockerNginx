# DockerNginx
Hướng dẫn thao tác đơn giản với nginx bằng Dockerfile
1. Tạo 1 thư mục trong ổ đĩa hiện tại
  mkdir test
2. Chuyển vào thư mục test
  cd test
3. Kết nối trang github
  git clone 
 4. Build image
  docker build -t mynginx .
 5. Build container
  docker run -it -p 80:80 mynginx
 6. Kiểm tra container
  docker ps
