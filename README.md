## Berikut adalah beberapa perintah Artisan Laravel yang sering digunakan:

# 1. Membuat file boilerplate:

- Membuat file controller baru.

```bash
php artisan make:controller <nama_controller>
```

- file model baru
```bash
php artisan make:model <nama_model>
```
- Membuat file migration baru
```bash
php artisan make:migration <nama_migration>
```

- Membuat file seeder baru.
```bash
php artisan make:seeder <nama_seeder>: Membuat file seeder baru.
```

- Membuat file 3 sekaligus model controller seeder migration baru.

```bash
php artisan make:model -m -c --Namacontroller <nama_model akan sama dengan controller>
```

- Membuat file test baru.
```bash
php artisan make:test <nama_test>
```

# 2. Menjalankan tugas:

- Membuat database kita fresh seperti baru dimigrate.
```bash
php artisan migrate:refresh 
```
-  Menjalankan server web development bawaan Laravel.
```bash
php artisan serve
```

- Membuka REPL (Read-Eval-Print Loop) Laravel.
```bash 
php artisan tinker
```
- Menjalankan unit test aplikasi.
```bash
php artisan test
```
- Menjalankan database seeder mengirim file ke database.
```bash
php artisan db:seed
```
- Mengoptimalkan aplikasi Laravel.
```bash
php artisan optimize
```
# 3. Mengelola aplikasi:
```bash
php artisan key:generate: Membangkitkan kunci enkripsi baru.
php artisan config:cache: Mencache konfigurasi aplikasi.
php artisan route:cache: Mencache rute aplikasi.
php artisan lang:publish: Menerjemahkan pesan bahasa.
php artisan phpinfo: Menampilkan informasi PHP.
```
