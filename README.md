# UML

### Class Diagram
<img src="./fe_buku/src/assets/ClassDiagram.drawio.png" alt="" width="500">

### ERD
<img src="./fe_buku/src/assets/ERD.png" alt="" width="500">

### Use Case Diagram
<img src="./fe_buku/src/assets/UseCase.png" alt="" width="500">

### Tampilan web
<img src="./fe_buku/src/assets/web3.jpeg" alt="" width="500">
<img src="./fe_buku/src/assets/web2.jpeg" alt="" width="500">
<img src="./fe_buku/src/assets/web1.jpeg" alt="" width="500">


## Konsep
Website ini adalah sistem pemesanan buku online yang memungkinkan pengguna untuk melihat katalog buku, menambahkan buku ke keranjang, dan melakukan pembayaran secara online. Aplikasi ini terdiri dari dua bagian utama: Backend (Express & Sequelize) dan Frontend (React & Vite).



### Model
- User (customer dan admin)
- Buku
- Keranjang
- Pesanan
- Pembayaran

### Relasi
- 1 customer mempunyai banyak keranjang
- banyak buku mempunyai 1 keranjang
- banyak keranjang mempunyai 1 pesanan
- 1 pesanan mempunyai 1 pembayaran