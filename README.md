# Web Foundations - 24330211002

## Identitas
- Nama: [ARIN CHERENITA RETTOB]
- NIM: 24330211002
- Mata Kuliah: Pemrograman Web: Fondasi Arsitektur Web

## Tujuan
Praktikum ini bertujuan untuk memahami fondasi arsitektur web,
komunikasi HTTP, request dan response, HTTP header, serta
workflow Git dan GitHub.

# Analisis HTTP

## 1. Google

- URL: https://www.google.com
- Method: GET
- Status Code: 200 OK
- Content-Type: text/html

### Request
Browser mengirim HTTP GET request kepada server Google
untuk meminta resource halaman web.

### Response
Server memberikan HTTP response kepada browser.
Status 200 OK menunjukkan bahwa request berhasil diproses.

---

## 2. GitHub

- URL: https://github.com
- Method: GET
- Status Code: 200 OK
- Content-Type: text/html

### Request
Browser mengirim HTTP GET request kepada server GitHub
untuk meminta halaman web.

### Response
Server mengirimkan response berupa halaman HTML kepada browser.

---

## 3. Wikipedia

- URL: https://www.wikipedia.org
- Method: GET
- Status Code: 200 OK
- Content-Type: text/html

### Request
Browser mengirim HTTP GET request untuk meminta halaman
Wikipedia.

### Response
Server mengirimkan halaman HTML kepada browser.

# HTTP Request dan Response

HTTP menggunakan model komunikasi request-response.
Client seperti browser mengirim request kepada server,
kemudian server memberikan response.

HTTP header membawa informasi tambahan mengenai request
dan response, seperti Content-Type, User-Agent,
Cache-Control, dan informasi lainnya.

# Git Workflow

Branch:
create-new-branch

Commit:
Menambahkan analisis HTTP tiga website.

Pull Request:
Branch create-new-branch akan diajukan ke branch main.

# Kesimpulan

Dari praktikum ini dapat dipahami bahwa browser bertindak
sebagai client yang mengirim HTTP request kepada server.
Server kemudian memberikan HTTP response yang berisi status,
header, dan resource yang diminta.

Selain memahami HTTP, praktikum ini juga memperkenalkan
workflow GitHub menggunakan branch, commit, push, dan
Pull Request.
