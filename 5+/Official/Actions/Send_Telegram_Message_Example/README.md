# Gravio Action to send free Telegram messages
This action is sending out Telegram messages for free using Gravio

## Requirement
- Gravio (free version is ok, you will need the HTTP Request component), download it from gravio.com
- Telegram Account
- Telegram Chat ID and Telegram Token
- Telegram Bot
- This assumes Gravio HubKit is running on Linux or mac

## Installation
- Import the `acs` file into the Gravio Actions editor
- add your `token prefix` and `token` after the `:`
- for sending the image, adjust the `file_within_actmgr_data_folder.jpg` to point to your file within `/home/gravio/hubkitrepo4/data/actmgr/data`

You are now ready to make the Telegram sending either messages or photo a part of your workflow, connecting it to IoT, AI or other events, which is what Gravio is built for.
