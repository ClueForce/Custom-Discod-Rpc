# Custom-Discod-Rpc

This is a Simple Discord Rich Precense

# Installation
1. First Step you must [Download Zip File](https://github.com/ClueForce/Custom-Discord-Rpc/releases/tab/1.0) from this Repo
2. Extact the Zip File
3. Go to `config.json` and Edit as you want, this is a Example `config.JSON`
```json
{
    "clientId": "Your Client Id",
    "rich_presence": {
        "details": "Line 1",
        "state": "Line 2",
        "assets": {
            "largeImageText": "Large Image Name",
            "largeImageKey": "Large-Image-Key",
            "smallImageText": "Small Image Name",
            "smallImageKey": "Small-Image-Key"
        },
        "buttons": {
            "primary": {
                "buttonLabelText": "Button 1",
                "buttonRedirectUrl": "https://yourlinkishere.com"
            },
            "secondary": {
                "buttonLabelText": "Button 2",
                "buttonRedirectUrl": "https://yourlinkishere.com"
            }
        },
        "timestamps": {
            "startTimestamp": null,
            "endTimestamp": null,
            "useTimer": false
        }
    }
}
```
if done, you must save changes!
4. Go to Console Command and type `node index.js` or `node .`
5. Done! you can use Discord Rich Precense now!

Example Discord Rich Precense

![Image](https://cdn.discordapp.com/attachments/818356648107966527/864775609792069702/owner-discussion-channel_-_Discord_7_14_2021_2_47_22_PM_2.png)

# Important
Discord-RPC will work if you use Discord APP, and Discord-RPC will not work if you use Discord Chrome

