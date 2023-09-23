# Hello world

"Hello, World!" adalah program paling sederhana yang biasanya digunakan untuk memperkenalkan suatu bahasa pemrograman.
Di dalam program "Hello, World!", Anda akan belajar cara mencetak pesan ke layar.

### Membuat Program "Hello, World!"
- Untuk membuat program "Hello, World!" dalam Rust, buat file baru dengan ekstensi .rs (misalnya, hello.rs).
- Buka file tersebut dengan teks editor atau IDE Rust yang sudah diinstal.

Struktur Dasar Program Rust:

```rust,noplaypen
fn main() {
    // Kode program akan ditulis di sini
}
```

Mencetak Pesan:

Berikut ini contoh program "Hello, World!" dalam Rust untuk  mencetak pesan ke layar.

```rust,editable
// Ini adalah komentar, dan diabaikan oleh kompiler.
// Anda dapat menguji kode ini dengan mengklik tombol "Run" di sana ->
// atau jika Anda lebih suka menggunakan keyboard, Anda dapat menggunakan pintasan "Ctrl + Enter".

// Kode ini dapat diedit, jadi jangan ragu untuk mengutak-atiknya!
// Anda selalu dapat kembali ke kode asli dengan mengklik tombol "Reset" ->

// ini adalah main function
fn main() {
    // Statements here are executed when the compiled binary is called.

    // Mencetak teks ke konsol
    println!("Hello World!");

}
```

Menjalankan Program:

- Buka terminal atau command prompt.
- Navigasikan ke direktori di mana Anda menyimpan file hello.rs.
- Jalankan program dengan perintah:

```bash
$ rustc hello.rs
```

`rustc` akan menghasilkan berkas biner `hello` yang dapat di jalankan.

```bash
$ ./hello
Hello World!
```
### Pemahaman Kode
`main()` adalah titik awal eksekusi untuk setiap program Rust. Ini adalah fungsi yang paling penting dalam program Rust, karena program Anda akan dimulai dari sini ketika dijalankan.

Setiap program Rust wajib memiliki fungsi `main()`. Ini adalah bagian yang pertama kali dieksekusi ketika Anda menjalankan program.

Fungsi `main()` dideklarasikan dengan menggunakan kata kunci `fn` diikuti oleh nama fungsi, yaitu `main`. Fungsi ini tidak menerima argumen.

Struktur dasar dari fungsi main() dalam Rust adalah sebagai berikut:
```rust,noplaypen
fn main() {
    // Kode program akan ditulis di sini
}
```

Semua pernyataan atau kode program yang ingin Anda jalankan di dalam program Rust Anda ditempatkan di dalam blok fungsi `main()`, yang diapit oleh tanda kurung kurawal {}.

Kode yang ada di dalam fungsi `main()` akan dieksekusi secara berurutan dari atas ke bawah ketika program dijalankan.

Kode dalam fungsi `main()` biasanya berisi perintah-perintah untuk melakukan tugas tertentu, seperti mencetak pesan ke layar, menghitung sesuatu, atau berinteraksi dengan pengguna.

Setelah fungsi `main()` selesai dieksekusi, program akan selesai dan keluar.

Fungsi `main()` adalah tempat di mana Anda biasanya memulai program Anda, dan dari sini Anda dapat memanggil fungsi-fungsi lain atau menjalankan kode yang Anda butuhkan.

Ini adalah salah satu bagian paling fundamental dalam pemrograman Rust, dan Anda akan menggunakannya di hampir setiap program yang Anda tulis.

Jadi, secara singkat, fungsi `main()` adalah fungsi yang menjadi titik awal dari eksekusi program Rust, dan di dalamnya Anda menuliskan kode untuk menjalankan tugas-tugas yang ingin Anda lakukan dalam program Anda.


`println!` merupakan [*macro*][macros] yang mencetak teks ke konsol.

### Eksperimen
Klik 'Run' di atas untuk melihat hasil yang diharapkan. Selanjutnya, tambahkan baris baru dengan `println!` macro kedua sehingga hasilnya menunjukkan:

```text
Hello World!
I'm a Rustacean!
```

### Kesimpulan
- Anda telah berhasil membuat dan menjalankan program "Hello, World!" dalam bahasa pemrograman Rust.
- Ini adalah langkah pertama dalam memahami dasar-dasar pemrograman Rust.

Dengan mengikuti langkah-langkah di atas, Anda akan dapat membuat dan menjalankan program "Hello, World!" dalam Rust. Hal ini akan membantu Anda memahami struktur dasar program Rust dan cara mencetak pesan ke layar.