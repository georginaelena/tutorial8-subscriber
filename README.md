# Tutorial 8
*Nama   : Georgina Elena Shinta Dewi Achti* <br>
*NPM    : 2206810995*<br>
*Kelas  : AdvProg-B*

# Refleksi 1

#### 1. Apa itu ***AMQP***?

AMQP adalah singkatan dari Advanced Message Queuing Protocol. Ini adalah protokol komunikasi yang digunakan untuk pertukaran pesan antara aplikasi dan sistem. Biasanya digunakan dalam sistem pengiriman pesan atau antrian pesan untuk mendukung komunikasi asinkron antara berbagai komponen perangkat lunak.

#### 2. Apa artinya? *guest:guest@localhost:5672*, apa itu guest pertama, dan apa itu guest kedua, dan untuk apa localhost:5672?

`guest:guest@localhost:5672` adalah URI koneksi yang digunakan untuk menjalin koneksi ke broker AMQP.

- `guest:guest`: Ini merujuk pada nama pengguna dan kata sandi yang digunakan untuk autentikasi saat terhubung ke broker AMQP. Kata pertama "guest" merupakan nama pengguna, sedangkan kata kedua "guest" adalah kata sandi.
- `localhost:5672`: Bagian ini menentukan nama host dan port dari broker AMQP. "localhost" mengacu pada mesin lokal tempat kode berjalan, menunjukkan bahwa broker berjalan pada mesin yang sama. Nomor port 5672 adalah port default untuk komunikasi AMQP.