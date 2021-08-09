# bansos
 Aplikasi Data Bantuan Sosial Pemerintah Kabupaten Ciamis.
 
Laravel Versi 8.0
Admin Panel Voyager

Setelah download repository, segera lakukan update composer.
`composer update`

copy+paste `.env.example` dan ubah menjadi `.env` sesuaikan dengan nama database, username dan password

lakukan migrasi database
`php artisan migrate`

lakukan instalasi voyager
`php artisan voyager:install --with-dummy`

Tambahkan symlink, agar data di storage dapat di akses public.
`php artisan storage:link`
