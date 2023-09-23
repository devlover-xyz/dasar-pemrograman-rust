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

`println!` merupakan [*macro*][macros] yang mencetak teks ke konsol.

Sebuah berkas biner dapat dihasilkan menggunakan kompiler Rust: `rustc`.

```bash
$ rustc hello.rs
```

`rustc` akan menghasilkan berkas biner `hello` yang dapat di jalankan.

```bash
$ ./hello
Hello World!
```

### Activity
Klik 'Run' di atas untuk melihat hasil yang diharapkan. Selanjutnya, tambahkan baris baru dengan `println!` macro kedua sehingga hasilnya menunjukkan:

```text
Hello World!
I'm a Rustacean!
```