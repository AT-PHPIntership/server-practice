# Bài tập server buổi 1.

1. Cài đặt 1 máy ảo `ubuntu` bằng vagrant và thực hành các lệnh đã học 
- Các lệnh trong slide
- Các lệnh trong file `linux_demo.md`
- các lệnh trong slide `easier linux`
2. Với mỗi lệnh mô tả ý nghĩa của lệnh và chụp lại ảnh màn hình 
3. Viết lại thành 1 document trên github issue với tiêu đề có cấu trúc như ví dụ sau :`S1-Le Mai Vien`

# Bài tập server buổi 2

### Cách thức: 
- Viết document trên github issue mô tả lại những gì đã được học gồm mô tả lệnh, chụp ảnh màn hình kết quả. 
- Document phải rõ ràng, có cấu trúc

### Nội dung
- Các lệnh về vagrant
  - vagrant box: list boxes, add box, remove box, export box
  - vagrant plugins: install plugin, list plugins, uninstall plugin
  - vagrant start, stop, reload
  - vagrant provision
  - Ý nghĩ của một số config cơ bản trong Vagrantfile: `config.vm.box`, `config.vm.network "forwarded_port"`, `config.vm.network "private_network"`, `config.vm.network "public_network"`, `config.vm.synced_folder`, `config.vm.provider`
- Cài đặt web server
  - Install apache
  - Install PHP
  - Install mysql
  - Show php hello world, show phpinfo
  - Config vhost
  - Kết nối tới mysql từ terminal, từ workbench
