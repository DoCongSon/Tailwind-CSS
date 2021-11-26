## cách cài dặt tailwind css

- bước 1: tạo file tailwind.css và thêm 3 dòng sau:
  ```css
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  ```
- bước 2: mở terminal gõ lệnh

  - `$ npm init -y`
  - `$ npm install -D tailwindcss postcss autoprefixer vite`

- bước 3: vào file package.json:
  Sửa dòng `"test": "echo \"Error: no test specified\" && exit 1"` thành `"dev": "vite"`

- bước 4: mở lại terminal và gõ lệnh `mpx tailwindcss init -p`
- bước 5: link file tailwind.css vào index.html và sử dụng
