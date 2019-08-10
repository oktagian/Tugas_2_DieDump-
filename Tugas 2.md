# Die Dump
Function dd() atau die dump biasanya digunakan untuk melakukkan debugging, dengan kata lain untuk memeriksa isi dari sebuah data.

dd() pada laravel akan langsung menghentikan script dari sebuah aplikasi / website ketika fungsi ini dipanggil.

## Contoh :

`$posts = Post::where('status','published')->get();`

`dd($posts);`

Maka, program akan menampilkan data / isi dari variable $posts, lalu menghentikan script setelahnya (apabila tersedia).

Metode ini tentu akan memudahkan para programmer / developer dalam melakukan _debugging_ atau mencari kesalahan dalam program yang mereka buat.
