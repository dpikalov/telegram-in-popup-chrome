# telegram-in-popup-chrome

This extenshon opens **www.telegram.org** in Popup page

## Motivation
Using https://web.telegram.org in Chrome **is not safe**.

When you open https://web.telegram.org, Chrome extensions (like e.g. adblock) **can read** your chats, as **they have full access** to any opened tabs. I.e. they can read everything in your chats / channels and send it to 3rd party servers.

**Telegram-in-popup-chrome** opens Telegram app in so called **Popup window** - this is special context, kind of sandbox in Chrome, **not  accessible from any other Chrome extensions**. This extension is basically just specially configured **manifest.json**, there is **no JS code inside** - i.e. there is no even technical possibility to steal your private data from telegram chats.

As Google rejected this extention due to Policy vioation (they don't allow to publish extensions with only functionaty to open 3rd party website) - the only option is to install it manually (see how-to below) 

## Video
[<img src="https://i.ytimg.com/vi/Q-CHQ58shWY/maxresdefault.jpg" width="50%">](https://studio.youtube.com/video/Q-CHQ58shWY)

## How to install it in Chrome
- Clone the  repo
- Open ```chrome://extensions``` in chrome
- Toggle ```Developer mode```
- Load unpacked > choose ```src``` folder



