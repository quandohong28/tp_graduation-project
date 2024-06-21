<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## FPT - Đồ án tốt nghiệp

### Mô tả


### Danh sách thành viên

<table border="1">
    <thead>
        <tr>
            <th>STT</th>
            <th>ID</th>
            <th>Name</th>
            <th>Link</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
        <tr>
            <td>1</td>
            <td>PH44316</td>
            <td>Đỗ Hồng Quân</td>
            <td>quandohong28</td>
        </tr>
    </tbody>
</table>

### Yêu cầu
- php >= v8.2
- composer
- node >= v20.13.1
- npm >= v10.5.2
- mysql
- apache2

### Thư viện sử dụng

- Vite
- Livewire
- Tailwindcss
- Socialite
- Scout
- Reverb: to make realtime chat

## Khởi chạy dự án

- Bước 1: Chạy câu lệnh `php artisan key:generate` để tạo key cho dự án

- Bước 2: Cài đặt các thư viện php và javascript: `composer i && npm i` hoặc `composer install && npm install`

- Bước 3: Thiết lập cơ sở dữ liệu
    + Tạo database, đặt tên là fpt_datn
    + Copy file .env.example -> đổi tên thành .env
    + Đặt giá trị cho DB_DATABASE=fpt_datn
    + Migrate database: `php artisan migrate`
    + Tạo dữ liệu fake: `php artisan db:seed`

- Chạy dự án dưới localhost: `php artisan serve && npm run dev`

- Build dự án: `npm run build`

