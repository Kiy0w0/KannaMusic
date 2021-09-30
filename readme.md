# Langkah
## Bikin Bot anda di developer portal
- Pergi Ke -> [Discord Developer portal](https://discord.com/developers/applications)
- Bikin Aplikasi baru+Bot baru,jika sudah punya bot yang lama bisa digunakan
- Bikin Bot invite Link disini -> [here](https://discordapi.com/permissions.html)
- Save bot token kalian
## Ambil Client & Client Secret Spotify Kalian Di link bawah ini!
- login [here](https://developer.spotify.com/dashboard/) Login/Bikin akun,kemudian Bikin aplikasi

# Installation

Click [![Run on Repl.it](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://repl.it/github/SudhanPlayz/Discord-MusicBot)

Then let it load the project, It may take 1 - 5 min.

Then you'll need to edit the `botconfig.js` and fill in the [Lavalink](https://github.com/freyacodes/Lavalink), Token, Discord_ClientID, Discord_ClientSecret, Spotify_ClientID, Spotify_ClientSecret.

> If you want to host lavalink on replit you can check out this [repo](https://github.com/DarrenOfficial/lavalink-replit)

### dashboard setup
* Add your replit url into your `botconfig.js`

![Example](https://i.imgur.com/JBuNrSe.png)
> Make sure that you use all lowercase, **there must be no capital letter.**

* Go to the Discord Developer Portal under the OAuth2 tab.

![BangOauth](https://i.imgur.com/miExkYt.png)
> Make sure that you use all lowercase, **there must be no capital letter.** also make sure to add `https://` and `http://`

### Final

Once done you can restart your bot, then invite it using this url template. https://discord.com/oauth2/authorize?client_id=CLIENT_ID&scope=bot%20applications.commands&permissions=2205280576

* CLIENT_ID needs to be replaced with your bot Id
* Permission calculator: [learn more](https://finitereality.github.io/permissions-calculator)
* You can use #generateInvite instead: [learn more](https://discord.js.org/#/docs/main/main/class/Client?scrollTo=generateInvite)
