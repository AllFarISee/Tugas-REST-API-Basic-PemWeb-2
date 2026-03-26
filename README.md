# REST API Mahasiswa

## Deskripsi
API sederhana menggunakan Node.js dan Express.js tanpa database.
Data disimpan dalam array (data dummy).

Running Server:
http://localhost:3000

## Endpoint

### 1. Testing Server
GET /
Response:
API Mahasiswa berjalan

### 2. GET data Mahasiswa
GET /students

### 3. GET Mahasiswa by ID
GET /students/:id

### 4. POST Tambah Mahasiswa
POST /students
Body JSON:
{
  "nama": "",
  "jurusan": ""
}

### 5. PUT Update data Mahasiswa
PUT /students/:id

### 6. DELETE Mahasiswa
DELETE /students/:id
