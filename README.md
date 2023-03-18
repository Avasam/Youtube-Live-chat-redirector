# Youtube Live chat redirector

A simple web page that redirects to the latest Youtube Live chat of a channel.  
Meant to be used as an OBS browser dock.

## Use as an OBS browser dock

1. Find your channel ID at <https://www.youtube.com/account_advanced>
2. Add a new custom browser dock:  
    ![New Custom Browser Docks...](/new-custom-browser-docks.jpg)
3. Add a new entry:  
    - Dock Name: Youtube Chat
    - URL: [https://avasam.github.io/Youtube-Live-chat-redirector?channelId=<your-channel-id\>](https://avasam.github.io/Youtube-Live-chat-redirector?channelId=)
    (replace `<your-channel-id>` by your channel ID found at step 1)

![Youtube Chat browser dock](/Youtube-Chat-browser-dock.jpg)

<!-- API key settings: https://console.cloud.google.com/apis/credentials/key/39e349b2-553c-427e-a549-35a775eafca2?project=youtube-live-chat-redirector -->
