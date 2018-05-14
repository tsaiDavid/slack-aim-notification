# slack-aim-notification
Bringing back your fondest memories with Slack + AIM notification sound

## Installation
*Note: The examples below assume you would like to replace the "Hummus" notification sound*

1. Locate the directory where your Slack resources are.
    * MacOS: `/Applications/Slack.app/Contents/Resources`
    
    ![](https://github.com/tsaiDavid/slack-aim-notification/blob/master/resources.png)

2. Backup the original notification sound you will be replacing

    * Simply rename `<original-slack-name>.mp3` to `<original-slack-name>.backup.mp3`
```
$ mv hummus.mp3 hummus.backup.mp3
```

3. Download and rename the AIM notification sound

    * [Download AIM notification sound from Google Drive](https://drive.google.com/file/d/1c0ofGgcYw4XgfZFGhZCiD6VHRLYFXqK3/view?usp=sharing)
    * Rename the downloaded `aim_receive.mp3` and place it where the existing notification MP3's are located

```
$ mv ~/Downloads/aim_receive.mp3 ~/Applications/Slack.app/Contents/Resources/hummus.mp3
```

4. Select your newly replaced Slack sound from settings

![](https://github.com/tsaiDavid/slack-aim-notification/blob/master/slack_settings.png)

5. Enjoy!
   * If you run into issues - try restarting Slack / clearing its cache

## Credits
  * AOL Instant Messenger
  * [Make Front End Shit Again](https://makefrontendshitagain.party/)
  * [Slack Black Theme by widget-](https://github.com/widget-/slack-black-theme)
