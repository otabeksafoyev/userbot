# Kaworai Userbot

Ishga tushirish (kaworai_bot papkasidan): `python -m userbot.main`

.env ga qo'shing:
  USERBOT_LOGIN_BOT_TOKEN=<@BotFather dan yangi bot>
  USERBOT_FERNET_KEY=<python -c "from cryptography.fernet import Fernet;print(Fernet.generate_key().decode())">
  USERBOT_AUTO_CONFIRM=0   # 1 bo'lsa tasdiqsiz qo'shadi (tavsiya etilmaydi)

Muhim: userbot akkaunti maxfiy kanal(lar)da ADMIN bo'lishi kerak (post yozish huquqi bilan).
Railway: alohida servis (Start command: python -m userbot.main), o'sha env va DATABASE_URL bilan.
