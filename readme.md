# Basic Golang CRUD API (+ JWT dan SQLite)

- Cara menjalankan: ''' go run . '''
- Sumber referensi: https://waynestalk.com/en/go-jwt-tutorial-en/
- CRUD ini dimodifikasi dengan tambahan berikut:
  - menambah endpoint baru:
    - POST /update (dengan token) untuk mengubah umur user berdasarkan token
  - menggunakan sqlite berbasis file (users.db), pada sumber referensi menggunakan In-Memory Databases