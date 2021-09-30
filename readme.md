# Langkah
## Bikin Bot anda di developer portal
- Pergi Ke -> [Discord Developer portal](https://discord.com/developers/applications)
- Bikin Aplikasi baru+Bot baru,jika sudah punya bot yang lama bisa digunakan
- Bikin Bot invite Link disini -> [here](https://discordapi.com/permissions.html)
- Save bot token kalian
## Ambil Client & Client Secret Spotify Kalian!
- login [Klik Disini](https://developer.spotify.com/dashboard/) Login/Bikin akun,kemudian Bikin aplikasi

# Penginstallan

Pencet [![Jalankan Projek ini](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://replit.com/github/CarameloSz/KannaMusic)

Tunggu Sampai replit kalian ke load 1-5 Menit!

Kemudian kamu bisa mengedit`botconfig.js` Dan isi Lava link kalian[Lavalink](https://github.com/freyacodes/Lavalink), Token, Discord_ClientID, Discord_ClientSecret, Spotify_ClientID, Spotify_ClientSecret.

> Jika kamu mau ngehost lavalink nya bisa lihat Contohnya -> [repo](https://github.com/DarrenOfficial/lavalink-replit)

### dashboard setup
* Tambahkan Bot url kalian ke `botconfig.js`

![Contoh](https://i.imgur.com/JBuNrSe.png)
> Pastikan Anda menggunakan huruf kecil semua, **Tidak ada yang huruf kapital.**

* Pergi ke Discord Developer Portal Di tab OAuth2.

![BangOauth](https://i.imgur.com/miExkYt.png)
> Pastikan Anda menggunakan huruf kecil semua, **tidak boleh ada huruf kapital.** juga pastikan untuk menambahkan `https://` dan `http://`

### Terakhir.

Setelah anda merestart bot anda, Kemudian Invite menggunakan Template ini. [Template](https://discord.com/oauth2/authorize?client_id=719506504058798141&permissions=2205280576&scope=bot%20identify%20guilds%20applications.commands&redirect_url=http://localhost/api/callback&response_type=code)

* CLIENT_ID perlu diganti dengan ID bot Anda
* Permission calculator: [Pelajari Lebih lanjut](https://finitereality.github.io/permissions-calculator)
* Kamu bisa menggunakan #generateInvite Sbg gantinya: [Pelajari Lebih lanjut](https://discord.js.org/#/docs/main/main/class/Client?scrollTo=generateInvite)
