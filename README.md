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

Example Discord Rich Precense :
![Image]()

# Important
Discord-RPC will work if you use Discord APP, and Discord-RPC will not work if you use Discord Chrome

