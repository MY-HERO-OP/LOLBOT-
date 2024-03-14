# LOLBOT v1.1.3 UX1 #IM #NF (Improvements/New Features)

<p align="center">
    <a href="https://github.com/">
        <kbd>
            <img width="450" src="https://telegra.ph/file/a73a7d59d4a139df59c16.jpg" alt="LOLBOT">
        </kbd>
    </a>

<div align=center>

----

[![](https://img.shields.io/github/repo-size/theRequestofficial/LOLBOT?color=blue&label=Repo%20Size&labelColor=333333)](#) [![](https://img.shields.io/github/commit-activity/m/theRequestofficial/LOLBOT?logo=github&labelColor=333333&label=Github%20Commits&color=red)](#) [![](https://img.shields.io/github/license/theRequestofficial/LOLBOT?style=flat&label=License&labelColor=333333&color=yellow)](#)|[![](https://img.shields.io/github/issues-raw/theRequestofficial/LOLBOT?style=flat&label=Open%20Issues&labelColor=333333&color=purple)](#) [![](https://img.shields.io/github/issues-closed-raw/theRequestofficial/LOLBOT?style=flat&label=Closed%20Issues&labelColor=333333&color=orange)](#) [![](https://img.shields.io/github/issues-pr-raw/theRequestofficial/LOLBOT?style=flat&label=Open%20Pull%20Requests&labelColor=333333&color=lightgrey)](#) [![](https://img.shields.io/github/issues-pr-closed-raw/theRequestofficial/LOLBOT?style=flat&label=Closed%20Pull%20Requests&labelColor=333333&color=green)](#)
:---:|:---:|
[![](https://img.shields.io/github/languages/count/theRequestofficial/LOLBOT?style=flat&label=Total%20Languages&labelColor=333333&color=teal)](#) [![](https://img.shields.io/github/languages/top/theRequestofficial/LOLBOT?style=flat&logo=python&labelColor=333333&color=lightblue)](#) [![](https://img.shields.io/github/last-commit/theRequestofficial/LOLBOT?style=flat&label=Last%20Commit&labelColor=333333&color=9cf)](#) [![](https://badgen.net/github/branches/theRequestofficial/LOLBOT?label=Total%20Branches&labelColor=333333&color=violet)](#)|[![](https://img.shields.io/github/forks/theRequestofficial/LOLBOT?style=flat&logo=github&label=Forks&labelColor=333333&color=ff69b4)](#) [![](https://img.shields.io/github/stars/theRequestofficial/LOLBOT?style=flat&logo=github&label=Stars&labelColor=333333&color=yellowgreen)](#)
[![](https://img.shields.io/badge/LOLBOT%20Updates%20Channel-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=333333)](https://t.me/Opleech) |[![](https://img.shields.io/badge/LOLBOT%20Support%20Unit-Join-9cf?style=for-the-badge&logo=telegram&logoColor=blue&style=flat&labelColor=333333)](https://t.me/WD_Topic_Group) |

</div>

---

## Readme Contents
- [Introduction](#introduction)
- [Features](#features)
- [Commands](#commands)
- [Usage](#usage)
- [Configure LOLBOT](#configure-LOLBOT)
- [Deployment](#deployment)
    - [VPS](#vps)
        - [Direct](#Run-directly-in-python)
        - [Docker](#Run-Using-Docker)     
    - [Render](#render)
- [Demo Bot](#demo-bot)
- [Creator Details](#creator-details)

## Wiki Content
- [Home](https://github.com//wiki)
- [Why LOLBOT?🤔](https://github.com//wiki/Why-LOLBOT%3F%F0%9F%A4%94)
- [Features🧩](https://github.com//wiki/Features%F0%9F%A7%A9)
- [Yet to Come 🎯](https://github.com//wiki/Yet-to-Come-%F0%9F%8E%AF)
- [Credits 🤝](https://github.com//wiki/Credits-%F0%9F%A4%9D)

# Introduction

**LOLBOT**, your personal AI assistant on Telegram, is designed to enhance your productivity by providing a seamless experience. With MongoDB integration, your data persist even if the bot restarts, ensuring you never miss a moment. Whether you're managing your schedule in private messages or coordinating group activities, LOLBOT has you covered.

**LOLBOT** developed from scratch by The Request's Cave Organization, it is a standalone project. 🥇

# Features

<p align="center">
    <a href="https://github.com/">
        <kbd>
            <img width="450" src="https://telegra.ph/file/23314d0629b4b25987223.jpg" alt="Feature_Pack">
        </kbd>
    </a>

<div align=center>
</div>

1. **Universal Usage and Portability:** 
    - Works seamlessly in both private messages and any Telegram group where the bot is an admin.♾️
    - We have included all the necessary fonts, graphics, and other elements in the repository to ensure LOLBOT functions as expected and to enhance its portability. 🧩

2. **Persistent Storage:** 
    - MongoDB integration for storing reminders and user data.💽
    - Reminders and other user data persist even if the bot restarts.

3. **Custom Timezones:** 
    - Set your preferred timezone for personalized reminder notifications.⌚

4. **Imporved Reminders Module:** ⏰
    - No limit on the number of reminders you can set in LOLBOT.
    - Recurring (repeating) reminders for minutely, hourly, daily, weekly, monthly, yearly time periods
    - View all active reminders under one command.
    - Edit Reminders function
    - Delete Reminders function

5. **Deployment Support:**
    - Deploy on both Render and VPS for flexible hosting options.🚀

6. **Meet Your Personal AI Assistant within LOLBOT**
    - LOLBOT can generate responses from Google's Most Powerful AI Modle aka Google Gemini. Simply put your API key in the LOLBOT and meet Gemini! 🤖
    - Global API setup or user's own API setup mechanism based on your preference.⚙️

7. **Chatbot powered by Google Gemini**
    - Feeling bored? Chat with LOLBOT! Play games with LOLBOT!! LOLBOT replies to anything you say with the support of Google's Gemini Pro.💬
    - Global API setup or user's own API setup mechanism based on your preference.⚙️
  
8. **Image analysis module powered up with Google Gemini**
    - Analyse or get descriptions about any of your images using LOLBOT! 🔎
  
9. **Automatically Setting Up Bot Commands**
    - No need to manually set up bot commands in BotFather. We got you. Soon as the bot is deployed bot commands will be set automatically📐

10. **Modern and Advanced Broadcast Module/ Super Improved Scheduled Broadcast Module**
    - Amplify your voice! Send important updates directly to all your audience with categorized broadcast menu (PM Only Broadcast, Group Only Broadcast, All Chat Broadcast).
      Designed with easy-to-use Telegram Inline Buttons. [Only Available to Pre-authorized users in config.env]
    - Be a time master with LOLBOT's Scheducast module. Schedule your important broadcast messages with a blink! 🌟

11. **Easily Update you LOLBOT using UPSTREAM_REPO:**
    - Just by sending /restart cmd You can update your LOLBOT bot to latest version. ⤴️
    
12. **External Ping Support:**
    - Integrated with Uptimerobot to keep Render instances online. 🏓

13. **Custom Ringtones:**
    - Type `/ringtones` to get 4 sample custom ringtones to improve the Reminders. Look at the `/help` message for more info 🎵
   
14. **All-in-One Calculators**
    - LOLBOT includes all the calculators you need for both day-to-day and academic use.
    - Designed using interactive telegram inline buttons
    - Basic Calculator ✅
    - Scientific Calculator ✅
    - Unit Converter ✅
        - Length 📏
        - Volume 💧
        - Area ⬛️
        - Weight/Mass ⚖️
        - Time ⏰
        - Speed 🚗💨
        - Pressure 💨⚖️
        - Energy ⚡️
        - Power ⚡️💪
        - Angle 📐
        - Data Spectrum 📶
        - Fuel Efficiency ⛽️
        - Temperature 🌡️
        - Cooking 🍽️

15. **Telegraph Image Uploading**
    - Upload any Telegram image to Telegraph and get an instant direct link to your image 🔺
    - Reply to any image as /uptotgph to see the magic! 🪄

16. **Logo Generator**
    - Enhance your creativity using LOLBOT's Logo Generator Plugin🧬
    - /logogen is your magic word! 🪄

17. **ShiftX (Advanced Multifile Converter Plugin)** 🔄️
    - What you want to convert?
        - Images?
        - Videos?
        - Documents?
        - Audios?
    - No need to go around websites to convert you files. LOLBOT got your back 🤝
    - More conversation pairs yet to come ♾️
    - Convert a wide range of files simply within the Telegram Interface 🔥
      
19. **Doc Spotter (Advanced Auto Filtering)**
    - Are you an admin that has a movie group? This plugin is for you.🫵
    - Feel the power of DocSpotter Plugin 💪
        - Multiple F-Sub chats (Channels or Groups)
        - IMDB info and poster fetching
        - Enable or disable IMDb in your preferences.
        - Button dashboard only has access to the user who searches keyword
        - Requested file received in Bot PM
        - Indexing any file type in telegram
        - Delete Indexed Files Easily
          
20. **Image Background Remover**
    - Easily Remove your Images Background Using LOLBOT's Background Remover 🖼️✂️
    - User own Personal and Global API mechanism for more flexibility 🦾

21. **Chat Cloner [Clonergram]**
    - Want to clone a group or channel? Leave it to LOLBOT, /clonegram is the magic word 💠
    - Working on both groups and channels ✔️
    - Clone only you selected message/file types only
        - Text Cloning ✅
        - Image Cloning ✅
        - File Cloning ✅
        - Stiker Cloning ✅
        - Audio Cloning ✅
        - Video Cloneing ✅
      
23. **IMDb Search**
    - Find your fav movies and TV shows using /imdb 🍿🎞️

24. **Info & Utility Modules**
    - Simple Modules that cloud be help to you in day-to-day telegram usage 📅
    - Status of LOLBOT 📈
        - See Database Usage for Each Database in LOLBOT (/database)
        - Find Your Telegram ID (/info)
        - Find Any Other user Telegram ID (/info)
        - Find Any Other chat(Channel/Group) Telegram ID (/info)
        - See a stats report about LOLBOT and Host Server (/overview)
        - /users Command for Owner to See LOLBOT Using User's and Group Chats list

25. **Commit Detector Function**
    - Keep updated about your fav GitHub repo within the telegram environment. This feature can detect new commits from any public repo and send them to your telegram channel(s)/group(s)🪄
    - Exclusively for LOLBOT deploying owners only 

# Commands

- `/start`: Initiate the bot and receive a warm welcome.👋
- `/help`: To get help message and more info.🤝
- `/broadcast`: Amplify your voice! Send important updates directly to all your followers.📢")
- `/scheducast`: Be a master of time. Schedule your broadcasts using LOLBOT's Scheducast module📢")
- `/gemini [text]`: Meet Your Personal AI Assistant, Google Gemini 🤖
- `/chatbot`: Chat with LOLBOT's Chatbot💬
- `/mygapi`: Setup Your Google G-API🔗
- `/analyze4to`: Start the image analyze using AI🔍
- `/showmygapi`: Check your current G-API ✅
- `/delmygapi`: Delete Your G-API from LOLBOT's Database 🗑️
- `/uptotgph`: Upload any telegram image to Telegraph and get instant direct link 🚀
- `/logogen`: Craft your own logo with endless possibilities. (with Support for adding your own graphics, frames and more) 🎨🖌️
- `/imdb` : Find your fav movies and TV shows using /imdb 🍿🎞️
- `/docspotter`: Advanced auto filter feature packed with all feature you need for file managing 🗃️
- `/erasefiles`: Delete indexed files easily ♻️
- `/shiftx`: Convert wide range of files using LOLBOT's ShiftX Plugin ♻️
- `/setreminder`: Set a reminder for a specific date and time.🗓️
- `/myreminders`: To see all your active reminders.📃
- `/editreminders`: Edit Your reminders✍️
- `/delreminder`: Delete unnecessary reminders in a flash 🗑️
- `/settimezone TIMEZONE`: Customize your preferred timezone for reminder notifications.⏳
- `/ringtones`: Get uncommon ringtone files for set to LOLBOT Reminder Bot.🎵
- `/info`: See User/Bot/Chat info 📜
- `/removebg`: Remove background from any image 🪄
- `/rbgusage`: See your RemoveBG API Usage 📈 
- `/moreinfo`: Unbox the secrets! Type /moreinfo for the full bot lowdown & bonus notes.📚
- `/database`: Get database stats 📊
- `/bsettings`: Config LOLBOT easily ⚙️
- `/restart`: Restart your bot and Update to the letest version ⤴️

**You can discover additional sub-commands within the /help command that may not be explicitly listed.**

# Usage

⚙️. **Start a Chat:**
   - Begin a conversation with the bot either by searching on Telegram or using the provided link.

⚙️. **Simple Commands:**
   - Use intuitive commands like `/start` to initiate the bot and `/setreminder` to schedule reminders.

⚙️. **Personalize Time Zone:**
   - Optionally set your preferred timezone using the `/settimezone` command.

⚙️. **Group Friendly:**
   - Set reminders effortlessly in groups by mentioning the bot (@YourBotUsername) followed by the `/setreminder` command.

⚙️. **Modern Broadcast**
   - Type /broadcast to start the broadcast module. Select Broadcast type and send your message need to broadcast

# Configure LOLBOT

This section provides detailed information on the required environment variables for configuring LOLBOT in the `config.env` file. These environment variables are essential for the proper functioning of your LOLBOT bot. Please follow the instructions below to set up your environment variables before running the bot.

## Required Environment Variables (🔴)

### Primary

1. **TOKEN** [🔴]
   - Description: Bot Token Generated by [BotFather](https://telegram.me/BotFather)
   - Example: `TOKEN=your_bot_token_here`
   
2. **MONGODB_URI** [🔴]
   - Description: Your MongoDB URI
   - Example: `MONGODB_URI=mongodb://username:password@localhost:27017/LOLBOT_database`
     
3. **OWNER** [🔴]
   - Description: Owner ID of LOLBOT
   - Example: `OWNER=123456789`
  
4. **UPSTREAM_REPO_URL** [🔴]
   - Description: Your fork repo URL or Official repo link
   - Example: `UPSTREAM_REPO_URL=https://github.com/`

### Secondary

1. **REMINDER_CHECK_TIMEZONE** [🔴]
   - Description: Set a global timezone for reminders.
   - Example: `REMINDER_CHECK_TIMEZONE=America/New_York`
   
2. **AUTHORIZED_USERS** [🔴]
   - Description: Give access to users special modules like broadcast, scheducast, etc. (comma-separated list of user IDs or usernames)
   - Example: `AUTHORIZED_USERS=123456789,987654321,147852369`

3. **SCEDUCAST_TIMEZONE** [🔴]
   - Description: Set a preferred timezone for the scheducast module.
   - Example: `SCEDUCAST_TIMEZONE=Asia/Tokyo`
   
4. **SCEDUCAST_TIME_OFFSET** [🔴]
   - Description: Set the correct time offset for the timezone you mentioned in SCEDUCAST_TIMEZONE. The offset should be in hours and minutes.
   - Example: `SCEDUCAST_TIME_OFFSET=9.5`
   - Explanation: If your local timezone is Asia/Colombo, and it is 5 hours and 30 minutes ahead of UTC, you should set this value to `5.5`.

## Optional But Recommended to Fill Environment Variables (🔶)

### LOLBOT Profile Setup

1. **SETUP_BOT_PROFILE** [🔶]
   - Description;
       - You have been advised to set SETUP_BOT_PROFILE environment variable to False after you set up your LOLBOT profile correctly during the first deployment using /bsettings to prevent unnecessary rate limit errors.
       - Set True to set up the LOLBOT profile automatically. If you keep this env as empty or False you will have to set the bot profile manually in BotFather 
   - Example: `SETUP_BOT_PROFILE=True`

2. **BOT_NAME** [🔶]
   - Description: Enter a new name for LOLBOT
   - Example: `BOT_NAME=L O L`
     
3. **BOT_ABOUT** [🔶]
   - Description: Enter a new about text for LOLBOT. ⚠️ Remember about Telegram about text limits. keep the about text shorter
   - Example: `BOT_ABOUT=LOLBOT is your All-in-One AI Personal Assistant 🤖`
     
4. **BOT_DESCRIPTION** [🔶]
   - Description: Enter a new description for LOLBOT
   - Example: `BOT_DESCRIPTION=LOLBOT is a personal AI assistant on Telegram that enhances productivity through the seamless integration of reminders, schedules, broadcasts, and many more features.🍃`


## Optional Environment Variables (🟩)

### Feature Configurations and Others

1. **DS_IMDB_ACTIVATE** [🟩]
   - Description: Set True or Flase to Enable or Disable IMDb Poster and Info in Doc Spotter Button List message
   - Example: `DS_IMDB_ACTIVATE=True`
     
2. **GH_CD_URLS** [🟩 (Required if GH_CD_CHANNEL_IDS ENV was Filled)]
   - Description: Fill in the repo URL in the format theRequestofficial/LOLBOT.
   - Example: `GH_CD_URLS=theRequestofficial/LOLBOT`
  
3. **GH_CD_CHANNEL_IDS** [🟩 (Required if GH_CD_URLS ENV was Filled)]
   - Description: Add the Channel ID(s)/Group ID(s) that you need to post-commit update.
   - Example: `GH_CD_CHANNEL_IDS=-100123456789`

4. **GH_CD_PAT** [🟩]
   - Description: Your GitHub Personal Authorization Token for 5000 requests per hour API calls.
   - Example: `GH_CD_CHANNEL_IDS=ujb32uvb579g29824t89v245h8`

5. **ENABLE_GLOBAL_G_API** [🟩]
   - Description: Enable Global API for AI-related features (True or False)
   - Example: `ENABLE_GLOBAL_G_API=True`
  
6. **GLOBAL_G_API** [🟩]
   - Description: Add your API key from [Google AI Studios](https://aistudio.google.com/app/apikey)
   - Example: `GLOBAL_G_API=urwgui598t42598bgt589t5`
     
7. **SHIFTX_MP3_TO_AAC_BITRATE** [🟩]
   - Description: Set a quality for MP3 to AAC Outputs. Set a value among 128k, 192k, 256k, 320k | 128k = Lowest quality, smallest file size / 320k = highest quality, largest file size.
   - Example: `SHIFTX_MP3_TO_AAC_BITRATE=192k`

8. **SHIFTX_AAC_TO_MP3_BITRATE** [🟩]
   - Description: Set a quality for ACC to MP3 Outputs. Set a value among 128k, 192k, 256k, 320k | 128k = Lowest quality, smallest file size / 320k = highest quality, largest file size.
   - Example: `SHIFTX_AAC_TO_MP3_BITRATE=256k`
  
9. **SHIFTX_OGG_TO_MP3_QUALITY** [🟩]
   - Description: Set a quality for OGG to MP3 Outputs. Set a value from 0 to 9 | 9 = Lowest quality, smallest file size / 0 = highest quality, largest file size.
   - Example: `SHIFTX_OGG_TO_MP3_QUALITY=5`
  
10. **SHIFTX_MP3_TO_OGG_QUALITY** [🟩]
   - Description: Set a quality for MP3 to OGG Outputs. Set a value from -1 to 10 | -1 = Lowest quality, smallest file size / 10 = highest quality, largest file size.
   - Example: `SHIFTX_MP3_TO_OGG_QUALITY=4`
     
11. **REMOVEBG_API** [🟩]
   - Description: Set a Global API Key for RemoveBG Plugin. Get one from [RemoveBG](https://www.remove.bg/dashboard#api-key)
   - Example: `REMOVEBG_API=abcdefgh12345678`

### Plugin On/Off

1. **GEMINI_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Gemini Text Plugin.
   - Example: `GEMINI_PLUGIN=True`

2. **CHAT_BOT_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Chatbot Plugin.
   - Example: `CHAT_BOT_PLUGIN=True`

3. **GEMINI_IMAGE_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Gemini Image Analysis Plugin.
   - Example: `GEMINI_IMAGE_PLUGIN=True`

4. **CALCULATOR_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Calculator Plugin.
   - Example: `CALCULATOR_PLUGIN=True`

5. **SCI_CALCULATOR_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Scientific Calculator Plugin.
   - Example: `SCI_CALCULATOR_PLUGIN=True`
  
6. **UNIT_CONVERTER_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Units Converter Plugin.
   - Example: `UNIT_CONVERTER_PLUGIN=True`

7. **TELEGRAPH_UP_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Telegraph Image Upload Plugin.
   - Example: `TELEGRAPH_UP_PLUGIN=True`
  
8. **LOGOGEN_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Logo Gen Plugin.
   - Example: `LOGOGEN_PLUGIN=True`
  
9. **DOC_SPOTTER_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Doc Spotter Plugin.
   - Example: `DOC_SPOTTER_PLUGIN=True`

10. **SHIFTX_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the ShiftX Plugin.
   - Example: `SHIFTX_PLUGIN=True`
     
11. **REMOVEBG_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the RemoveBG Plugin.
   - Example: `REMOVEBG_PLUGIN=True`
     
12. **IMDb_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the IMDb Plugin.
   - Example: `IMDb_PLUGIN=True`

13. **CLONEGRAM_PLUGIN** [🟩]
   - Description: Set to `True` or `False` to Enable or Disable the Clonegram Plugin.
   - Example: `CLONEGRAM_PLUGIN=True`

Make sure to replace the placeholder values with your actual configuration settings. These environment variables are crucial for customizing and configuring the behavior of your LOLBOT bot. Ensure that they are correctly set before running the bot to ensure its proper functionality.

If you have any questions or need further assistance, please refer to the documentation or reach out to the [LOLBOT support team.](https://t.me/WD_Topic_Group)

# Deployment

## 🚀VPS

~Pre-Requiremtnts
 - Make sure to install Python 3.10 installed in your Ubuntu system. If you only have a version like Python 3.8, Install Python 3.10 too

### Run directly in python
-------------------------------------------------------------------------------------

~Deploying Steps
1. Give a Star to `https://github.com/` 😉
2. Fork the Repo
3. Set up a MongoDB database and obtain the connection URI.
4. Rename `rename_me_as_config.env` as `config.env`
5. Fill `config.env` as described above
6. Clone the repository: `git clone https://github.com/your_username/LOLBOT.git`
7. To Creating Virtual Environment, Run `python3.10 -m venv venv` in your server terminal
8. Activate the virtual environment using `source venv/bin/activate` 
9. Install required Python packages: `pip install -r requirements.txt`
10. Update System `sudo apt update`
11. Install ffmpeg for ShiftX Plugin (Optional | If you skip installation, LOLBOT will dynamically install ffmpeg itself) `sudo apt install ffmpeg`
12. Run the bot: `python bot.py` or `python3 bot.py`

___All-in-One Deploy CMDs for VPS (Make Sure to install python3.10 in your server)___
```
deactivate
cd
rm -rf LOLBOT
git clone https://github.com/
cd LOLBOT
python3.10 -m venv venv
source venv/bin/activate
sudo apt update
sudo apt install ffmpeg
pip install -r requirements.txt
python3 bot.py
```

***Use a method like `Linux Screen` to keep your LOLBOT online 24/7 when using VPS deployment***

### Run Using Docker
-------------------------------------------------------------------------------------

~Deploying Steps
1. Give a Star to `https://github.com/` 😉
2. Fork the Repo
3. Set up a MongoDB database and obtain the connection URI.
4. Rename `rename_me_as_config.env` as `config.env`
5. Fill `config.env` as described above
6. Clone the repository: `git clone https://github.com/your_username/LOLBOT.git`
7. Run this
   ```
   docker build -t LOLBOT .
   ```
8. After building Docker Image, run this
   ```
   docker run -p 8000:8000 LOLBOT
   ```
9. Enjoy ✨


## 🚀Render

1. Give a Star to `https://github.com/` 😉
2. Fork the Repo
3. Edit and Fill necessary environment variables in config.env
4. Create a new web service in your render account and click "Build and deploy from a Git repository"
![Render1](https://telegra.ph/file/272a6339cefb39cd2cbf3.jpg)
5. Connect your GitHub account to render if you repo private other vise copy your public GitHub repo (Not recommended) and paste it to render dashbord
![Render2](https://telegra.ph/file/64d2374b90f02c16515c1.jpg)
6. Give a Name for you web service and fill `python bot.py` in Start Command. Follow provided photo
![Render3](https://telegra.ph/file/abc352875450e7207b611.jpg)
7. Select a Instance Type [Recommended: 512 MB (RAM) | Free$0/ month 0.1 CPU]
![Render4](https://telegra.ph/file/a94474e10aaddfb4f5dc8.jpg)
8. Click "Create Web Service" Button
![Render5](https://telegra.ph/file/23f6f6b7440ce10c54866.jpg)
9. Wait Until deploy complete. Keep alert in the log to check is there any errors. If you deploy success you need to get something like this in the log
![Render6](https://telegra.ph/file/f50f10b967db275a8a276.jpg)
10. After deploy complete, copy your Webhook URL (Something like https://{your_project_name}.onrender.com). You can find it in the top of your deployment page
![Render7](https://telegra.ph/file/36cbeb8b0d5e3e839f705.jpg)
11. Not go to https://uptimerobot.com/ and create an account, after that Fallow this, Click Add New Monitor Button > Monitor Type: HTTP(s) > Give any Friendly Name as you wish >
Fill URL (or IP) as this :- {your_render_webhook_url} > and click Create Monitor
![Render8](https://telegra.ph/file/9a4ccb39ee8a3cbd0f7e6.jpg)
12. Now Bot has successfully deployed to Render

# Demo Bot
- **Test the lestest version of code using this demo bot,**
- **Did you know you can make this bot your personal assistant? Not only can it handle reminders for you, but you can also use other plugins too as you needs. 🚀 However, for the best experience, we recommend deploying your very own LOLBOT!**

`Deployed in Render`
[LOLBOT](https://t.me/LOLBOT_Reminder_Bot)
   
# Creator Details

Crafted🔨 with 🖤 by 𝓣𝓱𝓮 𝓢𝓮𝓮𝓴𝓮𝓻

- **Name:** 𝓣𝓱𝓮 𝓢𝓮𝓮𝓴𝓮𝓻
- **Telegram:** [@WD_Request_Bot](https://t.m/WD_Request_Bot)
- **GitHub:** [GitHub Profile](https://github.com/MY-HERO-OP)

![LICENSE](https://www.gnu.org/graphics/gplv3-127x51.png) 

Proofreaded by, [@WD_Request_Bot](https://t.me/WD_Request_Bot) 📖✔️

Enhanced by,

    - OpenAI's GPT3.5 & GPT-4 🪄
    - Google Gemini ✨
    - Codeium 🦾

Feel free to connect with the creator for inquiries or support related to LOLBOT in [LOLBOT Support Unit](https://t.me/WD_Topic_Group).
Enjoy using LOLBOT and stay organized!

#LOLBOT #LOLBOT #Made_From_Scratch
