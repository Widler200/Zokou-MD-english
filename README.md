# Zokou-2.0 🚀

Zokou is a multi-device bot designed to enhance your WhatsApp conversations with useful and fun features. Whether it’s managing files, interacting with stickers, or facilitating group management, Zokou is here to assist you!

## Key Features ✨

- **File Download:** Zokou can download audio and video files from links you send, making it easy to share them with your contacts. 🎶📹

- **Sticker Export:** You can export stickers from Telegram and use them in your WhatsApp conversations by simply sending them to Zokou. 😄✨

- **Group Management:** Zokou offers group management features like adding or removing members, configuring rules, and other settings. 👥📋

- **Text to Image:** The best logos have been selected for your convenience. 🖼️🎨

## Fun Features 🎉

- **Jokes and Riddles:** Zokou comes with a collection of jokes and riddles to add fun to your conversations. 😂🤔

- **Inspiring Quotes:** Receive inspiring quotes daily to motivate you. 💪🌟

## How to Get Zokou 🛠️

1. Click on **[Fork](https://github.com/luffy8979/Zokou-MD-english/fork)** to copy the repo to your GitHub account. Don’t forget to add a star 🌟 to encourage the developers.

2. Obtain a bot session: 

- [Session-1](https://zkscan.onrender.com)  
- [Session-2](https://zokouscan-din3.onrender.com)

3. Deploy Zokou
- **Heroku Deployment:**
1. If you don’t have a **Heroku** account, click [**here**](https://id.heroku.com/login) to create one.
2. Click [**here**](https://dashboard.heroku.com/new?template=https://github.com/luffy8979/Zokou-MD-english) to deploy the bot on **Heroku**.

- **Koyeb Deployment:**
1. If you don’t have a **Koyeb** account, click [**here**](https://app.koyeb.com/auth/signup) to create one.
2. Click the button below to deploy:

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=zokouve&type=docker&image=docker.io%2Fluffy077%2Fzokouve%3Alatest&env%5BPREFIX%5D=.&env%5BAUTO_READ_STATUS%5D=yes&env%5BAUTO_DOWNLOAD_STATUS%5D=yes&env%5BPM_PERMIT%5D=no&env%5BBOT_NAME%5D=Zokou-MD&env%5BBOT_MENU_LINKS%5D=https%3A%2F%2Fi.pinimg.com%2F736x%2F0a%2F70%2F6f%2F0a706f90d6a1fb39919aedfbb7fdd8d3.jpg&env%5BPUBLIC_MODE%5D=yes&env%5BDATABASE_URL%5D=create+on+koyeb&env%5BOWNER_NAME%5D=Djalega%2B%2B&env%5BNUMERO_OWNER%5D=22891733300&env%5BWARN_COUNT%5D=3&env%5BSTARTING_BOT_MESSAGE%5D=yes&env%5BPRESENCE%5D=1&env%5BPM_CHATBOT%5D=no&env%5BSESSION_ID%5D=put+your+session&env%5BANTI_VIEW_ONCE%5D=yes&ports=8000%3Bhttp%3B%2F)

- **Render Deployment:**
1. If you don’t have a **Render** account, click [**here**](https://dashboard.render.com) to create one.
2. Create a new web service.  
3. Choose **Public Git Repository**.  
4. In the field, enter `https://gitlab.com/bankai421341/zabimaru.git`.
5. Click **Connect**.  
6. Select the **Free Plan** if you don’t want to pay.
7. In the **Environment Variable** section, click **Add from .env** and copy the content below:

```env
PREFIX=.
AUTO_READ_STATUS=yes
AUTO_DOWNLOAD_STATUS=yes
PM_PERMIT=no
BOT_NAME=Dex
BOT_MENU_LINKS=LUFFY
PUBLIC_MODE=No
HEROKU=no
OWNER_NAME=Dex
NUMERO_OWNER=55589897
WARN_COUNT=3
STARTING_BOT_MESSAGE=yes
PRESENCE=3
PM_CHATBOT=no
SESSION_ID=Zokou-MD-WHATSAPP-BOT;;;=>eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoia0VKd1VpV0hYV3VJM1NYcXMyci81T0UyeVRrSTJxUXhSbGVuVlZuWEVHOD0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiYVk0ZXNtc1lKVjhrREd0VzdxSjd2UkZIaVJHYUVQb3pVNGNTQzQ5Vk8xOD0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJRRFNPcnAzWFFoa05GbGNBSEdHZDFYeWdhQ05xU3hrU09tMmtUY2RQaFVZPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJGUmlwenR3WXJ2YXZRbEMyQWR2SlJIWVlVb01FVXNWc1lLbUpzNWpMZWdnPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IlFHMmw1ZW9TcUdHVjFETGFJTThjNTVmL1JhVDdON3ZGcmpKcW5ZSEYyVlk9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkN3aXhMSG5Ld1R2Y0VUejZDYi9KOUhWY0c3SzdsYzJvTFJOVlQwZjBzMTg9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiK0RKenI5MWt6OFZKalRQWGltM0l3bVJCR25yUDhPWlNiUXY5Ni9HbUMzcz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiakN5bEh0ci84SHdCZkk3K3lnZy8rbUQyejl4WExGUWZDWHdBcm51dVNUST0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6InRRRjlGWDdZd3NHTUpNbFRrZEt4OFdEU1AyNFpqemo5UXFHRWozSzBCKzhOVmdkWjdHY0lHUjZ3ZnRSRHZiaSs3MWVRZW05Qk1KZ3JTQ3dRQmJHMWlBPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MTgsImFkdlNlY3JldEtleSI6Imh2OXpNcE81YzZ3L25NeUtvTndieWZQZkswYXJMSnJzSFJmRXp4VC9DK1U9IiwicHJvY2Vzc2VkSGlzdG9yeU1lc3NhZ2VzIjpbXSwibmV4dFByZUtleUlkIjozMSwiZmlyc3RVbnVwbG9hZGVkUHJlS2V5SWQiOjMxLCJhY2NvdW50U3luY0NvdW50ZXIiOjAsImFjY291bnRTZXR0aW5ncyI6eyJ1bmFyY2hpdmVDaGF0cyI6ZmFsc2V9LCJyZWdpc3RlcmVkIjp0cnVlLCJwYWlyaW5nQ29kZSI6IktOWTc1WEZIIiwibGFzdFByb3BIYXNoIjoiM2dQVUprIiwicm91dGluZ0luZm8iOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJDQWdJRFE9PSJ9LCJtZSI6eyJpZCI6IjUwOTU1NTg5ODk3OjdAcy53aGF0c2FwcC5uZXQiLCJuYW1lIjoi5YaG4oaQX+KGkGwg6pmw8J2Sn/Cdmo7wnZGLbCDqmbDihpBf4oaQ5YaGIiwibGlkIjoiMTg2MTI3MzIzNTIxMTk3OjdAbGlkIn0sImFjY291bnQiOnsiZGV0YWlscyI6IkNMZTAwN01DRUtyVzNzRUdHQUVnQUNnQSIsImFjY291bnRTaWduYXR1cmVLZXkiOiJTR3ljU21uOHJiQlJKMGlUdVNNTklCcUVXL0tBZFo1RUdkeTRRZzhSeTNnPSIsImFjY291bnRTaWduYXR1cmUiOiJyekZUMEJpQnVkUTNGck0xa2hoS1VwOVNZMTU3ZHVuQ3lXRXNVbjNNYlRxaG9QUEwweitjdUNHWlBNMjNNOUhHbVh0cUoxVldqQUxDdmk3RXVjWCtEQT09IiwiZGV2aWNlU2lnbmF0dXJlIjoiRnpOdXpadktNZVFSOXk3dXdGVjV2UlVDWDhscFI2aytmY3BORndnZVZpY0JCQnJteHM2L2gyeXZON29MSUhGKzYrbThyMEMrSHhndjdXVitZekFKaXc9PSJ9LCJzaWduYWxJZGVudGl0aWVzIjpbeyJpZGVudGlmaWVyIjp7Im5hbWUiOiI1MDk1NTU4OTg5Nzo3QHMud2hhdHNhcHAubmV0IiwiZGV2aWNlSWQiOjB9LCJpZGVudGlmaWVyS2V5Ijp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQlVoc25FcHAvSzJ3VVNkSWs3a2pEU0FhaEZ2eWdIV2VSQm5jdUVJUEVjdDQifX1dLCJwbGF0Zm9ybSI6InNtYmEiLCJsYXN0QWNjb3VudFN5bmNUaW1lc3RhbXAiOjE3NDg0Nzg3NjcsIm15QXBwU3RhdGVLZXlJZCI6IkFBQUFBTE9SIn0=
ANTI_VIEW_ONCE="yes
ANTI_COMMAND_SPAM=yes
ANTI_DELETE_MESSAGE=yes
AUTO_REACT_MESSAGE=no
```

8. Click **Add env** to save, then edit as needed. Don’t forget to enter your session ID.
9. Click **Deploy Service** and enjoy!

    
- **Github Deployement**

Sorry Removed , Suggest you to deploy on panel instead

## Contributions 🤝

Contributions to Zokou are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to open an issue or submit a pull request. 🙌

Special thanks to:

- **Fatao**, who added commands (Fancy, GPT, Dall-e, APK)  
- **CrazyPrice**, who hosted a second website for the session_id  

## License 📜

The WhatsApp Bot Zokou is released under the [MIT License](https://opensource.org/licenses/MIT).

Enjoy the diverse features of Zokou to enhance your WhatsApp experience! 💬🎉

## Developers:

- [**Djalega++**](https://github.com/djalega8000/Zokou-MD/)
- [**᚛M๏𝓷keℽ D Lบffy᚜**](https://github.com/Faouz995)
