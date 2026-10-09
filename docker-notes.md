"docker images": để xem các images đã tải
"docker ps": để xem các container đang chạy
"docker ps -a": để xem cả những containter đã dừng

"docker run -d -p 8081:80 --name web nginx"
"-d": chạy ngầm
"-p 8081:80": nối port 8081 trên máy với port 80 trên docker
"--name": đặt tên

"docker logs web": logs container
"docker start": start container
"docker stop": stop containter

"docker exec -it web bash": để vào terminal của container
"exit": để thoát

"docker cp index.html web:/usr/share/nginx/html/index": để nội dung index vào index của web

"docker rm -f web": để xóa container
