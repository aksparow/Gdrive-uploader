[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Upload to Google Drive Bot

Here Is Live Version Of Bot  [U2GD_Bot](http://telegram.dog/U2GD_Bot)

### How Can We Use It
  - First authorize Bot Using `/auth` command Generate a Key and send it To bot .
  - Now You can Send Supported Link To Bot.

### Available Commands
  - `/start` =  Start Message
  - `/auth` = Authorize You
  - `/revoke` = Delete Your Saved Credentials
  - `/help` =  Help Text

## Supported Links :
 - Direct Link
 - Mega.nz Link
 - Open load link (disabled)
 - Dropbox Link

## Requirements
  - [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (Others type)  `Required`
  - Telegram Bot Token (Using BotFather)  `Required`
  - Open load ftp login and Key  `Optional`
  - Mega Email and Password  `Optional`

 ` If You  wanna Change Openload Api and Mega Email Password You Can Change it From Given Path`
   - Mega => Plugins > TEXT.py
   - Open load  => Plugins > dlopenload.py

## Setup Your Own Bot
  - Create Your  [Google Drive api Credential](https://console.cloud.google.com/apis/credentials) (other type) and Download its json
  - Paste it In Bot Root Directroy  and Rename it "client_secrets.json"
  - Replace Your Bot Token in  [creds.py file](./creds.py)
  - Your Bot is Ready to Host.

### You can use Heroku to host it.

  - Make sure You have Changed Your Bot Token and google client api Before Hosting It`

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Originally Created by Aryan Vikash at https://github.com/aryanvikash/Google-Drive-Uploader

### Licence
  - GPLv3
