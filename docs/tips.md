
1) Create a Webhook on GitHub
2) Point to the Webhook URL to Hookdeck
3) Config Hookdeck in your Desktop Machine



## Hookdeck  login with github

**https://console.hookdeck.com/**

## Run on Terminal
### Start Hookdeck
hookdeck login --cli-key 12fmc1ff6d5jd1bxt2vbbrkwkhur1zy1ypd35vhdsotvxn9d7t

### Monitor Path
hookdeck listen 8071 source --cli-path /monitor

### To logout
hookdeck logout


* To create a web Hoock
> hookdeck listen 8071 source --cli-path /monitor
