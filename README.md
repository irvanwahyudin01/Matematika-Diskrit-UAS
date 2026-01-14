# Tugas Ujian Akhir Semester Mata Kuliah Matematika Diskrit

Nama   : Irvan Wahyudin <br>
Nim    : 312510359 <br>
Kelas  : TI.25.C5 <br>

Dosen : Dr. Muhamad Fatchan, S.Kom., M.Kom. <br><br>
penjelasan singkat silahkan lihat dan klik [Disini](https://youtu.be/2kWPS2pQbTU)
##  Implementasi Graph Menggunakan Adjacency List dengan DFS dan BFS (Python)

<table boder="0"><tr>
<td valign="top"><h3>CODE PYHTON</h3>
<img src="https://github.com/irvanwahyudin01/Matematika-Diskrit-UAS/blob/main/img/uasmtk1.png" width="450" height="450"><br>
<img src="https://github.com/irvanwahyudin01/Matematika-Diskrit-UAS/blob/main/img/uasmtk2.png" width="450" height="450"><br>
<img src="https://github.com/irvanwahyudin01/Matematika-Diskrit-UAS/blob/main/img/uasmtk3.png" width="450" height="450"></td></tr></table>
<h2>PENJELASAN PROGRAM</h2><ol>
  
##  Deskripsi
Repository ini berisi implementasi **struktur data Graph** menggunakan representasi **Adjacency List** serta penerapan algoritma traversal graf **Depth First Search (DFS)** dan **Breadth First Search (BFS)** menggunakan bahasa pemrograman **Python**.

---

## Konsep Dasar

###  Graph
Graph adalah struktur data yang terdiri dari:
- **Vertex (Simpul)** → merepresentasikan objek
- **Edge (Sisi)** → merepresentasikan hubungan antar objek

Graph yang digunakan pada program ini adalah **graf tidak berarah**, sehingga setiap hubungan berlaku dua arah.

---

###  Adjacency List
Adjacency List adalah metode representasi graph dengan menyimpan daftar tetangga dari setiap simpul dalam bentuk list.


#### Kelebihan Adjacency List:
- Lebih hemat memori
- Efisien untuk graph dengan jumlah sisi sedikit
- Mudah digunakan untuk traversal DFS dan BFS

---

##  Struktur Program

Program diimplementasikan menggunakan paradigma **Object-Oriented Programming (OOP)** dengan satu class utama, yaitu `Graph`.

###  Class `Graph`

#### `__init__(vertices)`
Constructor untuk:
- Menentukan jumlah simpul (vertex)
- Membuat adjacency list kosong sesuai jumlah simpul

#### `add_edge(u, v)`
Digunakan untuk menambahkan sisi antara simpul `u` dan `v`.  
Karena graph tidak berarah, maka:
- `u` ditambahkan ke daftar tetangga `v`
- `v` ditambahkan ke daftar tetangga `u`

---

## Algoritma Traversal

### Depth First Search (DFS)
DFS adalah algoritma penelusuran graph yang menjelajahi simpul **sedalam mungkin** sebelum berpindah ke simpul lain.

#### a. DFS Rekursif
Menggunakan pemanggilan fungsi secara berulang (rekursi).

**Langkah-langkah:**
1. Tandai simpul sebagai telah dikunjungi
2. Cetak simpul
3. Kunjungi tetangga yang belum dikunjungi

#### b. DFS Iteratif
Menggunakan struktur data **stack** sebagai pengganti rekursi.

**Keunggulan:**
- Menghindari batas maksimum rekursi
- Lebih aman untuk graph berukuran besar

---

### Breadth First Search (BFS)
BFS menelusuri graph berdasarkan **level atau jarak terdekat terlebih dahulu**.


---
### Dokumentasi Saat Program Dijalankan
<P><img src="https://github.com/irvanwahyudin01/Matematika-Diskrit-UAS/blob/main/img/uasmtk4.png" width="250" height="150">
