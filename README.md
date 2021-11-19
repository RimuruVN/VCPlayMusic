<p align="center"><a href="https://t.me/VeezMusicBot"><img src="https://image.lag.vn/upload/news/21/09/15/tensei-shitara-slime-datta-ken-tap-48-7_QLNX.jpg"></a></p>
<p align="center">
    <br><b>Rimuru Music là một dự án bot Telegram cho phép bạn phát nhạc trên nhóm trò chuyện thoại trên Telegram</b><br>
</p>


<h3>Yêu cầu 📝</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7 or higher
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
- [MongoDB](https://cloud.mongodb.com/)
- [2nd Telegram Account](https://telegram.org/blog/themes-accounts#multiple-accounts) (needed for userbot)

### 🧪 Nhận `SESSION_NAME` từ bên dưới:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py) ``Pyrogram``

### 🎖 Lịch sử

[![Mentioned in Awesome Python](https://awesome.re/mentioned-badge.svg)](https://github.com/RimuruVN/VCPlayMusic)

## Features 🔮

- Hỗ trợ hình thu nhỏ
- Hỗ trợ danh sách phát
- Youtube, hỗ trợ phát lại cục bộ
- Bảng cài đặt
- Điều khiển bằng các nút
- Tự động tham gia userbot
- Hỗ trợ lựa chọn bàn phím để chơi trên youtube
- Lyrics Scrapper
- Hàng đợi không giới hạn
- Bot phát sóng
- Người thu thập thống kê
- Chặn / Bỏ chặn (hạn chế người dùng sử dụng bot của bạn)

## Lệnh 🛠

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper

#### Admins Only 👷‍♂️
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/music on` - to disable music player in your group
- `/music off` - to enable music player in your group
- `/join` - invite assistant to your chat
- `/leave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/unauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel

### Sudo User 🧙‍♂️
- `/stats` - see the bot statistic
- `/leaveall` - order the assistant to leave all groups
- `/eval (query)` - execute any code
- `/sh (query)` - run any code

### Owner Only 👨🏻‍✈️
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

## 🔎 Inline Search Support
- just type the bot username in any chat, example: "`@VeezMusicBot Faded Alan Walker`", then bot will give you a results of the query you search in inline mode.

## Heroku Deployment <img src="./etc/Kenpurple.gif" width="40px">
The easy way to host this bot, deploy to Heroku, Change the app country to Europe (it will help to make the bot stable).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/RimiruVN/VCPlayMusic)

## VPS Deployment 📡

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/RimuruVN/ # clone the repo.
cd VeezMusic
pip3 install -U -r requirements.txt
cp example.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 main.py # run the bot.
```
