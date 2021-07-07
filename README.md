# Instagram Bot


You can Download almost anything From your Instagram Account.

**What Can Be Downloaded?:**
```
1. Semua posting dari Profil apa pun. (Baik Publik dan Pribadi, untuk profil pribadi Anda harus menjadi pengikut.)
2. Semua Postingan dari feed Anda.
3. Cerita dari profil apa pun (Baik Publik maupun Pribadi, untuk profil pribadi Anda harus menjadi pengikut.)
4. DP profil apa saja (Tidak perlu difollow)
5. Daftar Pengikut dan Pengikut dari Profil apa pun.
6. Daftar pengikut yang mengikuti kembali nama pengguna yang diberikan.
7. Daftar pengikut yang tidak mengikuti kembali nama pengguna yang diberikan.
8. Kisah Pengikut Anda.
9. Tagged posting dari profil apapun.
10. Postingan Anda yang disimpan.
11. video IGTV.
12. Sorotan dari profil apa pun.
13. Setiap Postingan Publik dari Tautan (Post/Reels/IGTV)

```

**Available Commands and Usage**
```
/start - Periksa apakah bot hidup.
/restart - Restart bot (Jika Anda mengacaukan sesuatu gunakan /restart.)
/help - Menampilkan menu ini.
/login - Masuk ke akun Anda.
/logout - Keluar dari akun Anda.
/account - Menampilkan detail akun yang masuk.

/posts <username> - Unduh posting dari nama pengguna apa pun. Gunakan /posts untuk mengunduh posting sendiri atau /posts <nama pengguna> untuk orang lain.
Contoh : /posts syridwan

/igtv <username> - Unduh video IGTV dari nama pengguna yang diberikan. Jika tidak ada nama pengguna yang diberikan, unduh IGTV Anda.

/feed <jumlah postingan untuk diunduh> - Mengunduh postingan dari feed Anda. Jika tidak ada nomor yang ditentukan, semua postingan dari feed akan diunduh.
Contoh: /feed 10 untuk mendownload 10 postingan terbaru dari feed.

/saved <jumlah posting untuk diunduh> - Mengunduh posting Anda yang disimpan. Jika tidak ada nomor yang ditentukan, semua posting yang disimpan akan diunduh.
Contoh: /saved 10 untuk mengunduh 10 posting tersimpan terbaru.

/followers <username> - Dapatkan daftar semua pengikut dari nama pengguna yang diberikan. Jika tidak ada nama pengguna yang diberikan, maka daftar Anda akan diambil.
Contoh: /followers syridwan

/followees <username> - Dapatkan daftar semua pengikut dari nama pengguna yang diberikan. Jika tidak ada nama pengguna yang diberikan, maka daftar Anda akan diambil.

/fans <username> - Dapatkan daftar pengikut yang mengikuti kembali nama pengguna yang diberikan. Jika tidak ada nama pengguna yang diberikan, daftar Anda akan diambil.

/notfollowing <username> - Dapatkan daftar pengikut yang tidak mengikuti kembali nama pengguna yang diberikan.

/tagged <username> - Mengunduh semua posting di mana nama pengguna yang diberikan ditandai. Jika tidak ada yang diberikan, posting Anda yang ditandai akan diunduh.

/story <username> - Mengunduh semua cerita dari nama pengguna yang diberikan. Jika tidak ada yang diberikan, cerita Anda akan diunduh.

/stories - Mengunduh semua cerita dari semua pengikut Anda.

/highlights <username> - Mengunduh sorotan dari nama pengguna yang diberikan, Jika tidak ada yang diberikan sorotan Anda akan diunduh.
```

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/justteen/IGBOT)

While Deploying fill `INSTA_SESSIONFILE_ID`, either by running [generate_instagram_session.py](https://github.com/subinps/Instagram-Bot/blob/main/generate_instagram_session.py]) in terminal or using /login after deploy or use [repl.it](https://replit.com/@justteen/generateInstagramSession)

For Generating Session after deployment, You Must leave the Variable as blank and fill manually after generating `INSTA_SESSIONFILE_ID` from your bot by sending /login.


### Deploy to VPS

```sh
git clone https://github.com/subinps/Instagram-Bot
cd Instagram-Bot
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 main.py
```

### Variables

* `API_HASH` API Hash from [my.telegram.org](https://my.telegram.org/)
* `API_ID` API ID from [my.telegram.org](https://my.telegram.org/)
* `BOT_TOKEN` Bot token from [@BotFather](https://telegram.dog/BotFather)
* `OWNER_ID` Telegram Id of Owner.
* `INSTAGRAM_USERNAME` Your Instagram username
* `INSTA_SESSIONFILE_ID` Your Instagram session file ID. Generate either by running [generate_instagram_session.py](https://github.com/subinps/Instagram-Bot/blob/main/generate_instagram_session.py]) in terminal or using /login after deploy or use [repl.it](https://replit.com/@subinps/generateInstagramSession)


### Note

```
Contributions are welcomed, But Kanging and editing a few lines wont make you a Developer.
Fork the repo, Do not Import code.

```

#### Support

Connect Me On [Telegram](https://telegram.dog/subinps_bot)


```
LEGAL DISCLAIMER

Developer or his team won't be liable for any loss caused by MISUSE of this Script.
This Bot is Indended to be used only for Educational Purposes.

```
