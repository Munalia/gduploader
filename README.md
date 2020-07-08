[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

# Upload to Google Drive Bot

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


### You can use Heroku to host it.

  - Make sure You have Changed Your Bot Token and google client api Before Hosting It`

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


### Licence
  - GPLv3
