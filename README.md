𓅽  pkg update && pkg upgrade -y
pkg install nodejs git ffmpeg imagemagick wget -y

𓅽  Clone your bot
git clone https://github.com/coaster/ultimate-bot.git
cd ultimate-bot

𓅽  Install dependencies
npm install @whiskeysockets/baileys express mongoose qrcode-terminal dotenv

𓅽 Run the bot
node bot.js
