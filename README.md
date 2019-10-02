# Rasa-ChatHistory-Logger

Chat history logger built for logging the conversations to json file using Custom Tracker Store

## Files description:
- **chatHistoryLogger.py** : Contains the Custom Tracker Store code logic, 
                             for more info refer: https://rasa.com/docs/rasa/api/tracker-stores/#custom-tracker-store
                             
- **chatLogger.py** : module for logging the chathistory data to json file                            

## Implementation

**Step 1** : Copy the *chatHistoryLogger.py* & *chatLogger.py* files into your project directory

**Step 2** : In your endpoints.yml put in the module path of the chatHistoryLogger.py, for example refer the below image

![ScreenShot](https://github.com/JiteshGaikwad/Rasa-ChatHistory-Logger/blob/master/endpoints_yml.PNG)

Once you have followed the above steps, start your bot and once you start interacting with the bot, you will find directory created named as ***chatHistoryLogs*** within your project directory, where you will find the chat histroy logs file based on the date it was created.
