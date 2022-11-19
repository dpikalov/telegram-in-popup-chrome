# telegram-in-popup-chrome

This chrome-extenshon opens **www.telegram.org** in Popup page

## Motivation
Using https://web.telegram.org in Chrome **is not safe**.

When you open https://web.telegram.org, other installed Chrome extensions (like e.g. adblock) **can read** your chats, as **they have full access** to any opened tabs. I.e. they can read all content in your Telegram tab and send it to 3rd party servers.

**Telegram-in-popup-chrome** opens Telegram app in so called **Popup window** - this is special, secured context, kind of sandbox in Chrome, **not  accessible from any other Chrome extensions**. This extension is basically just specially configured **manifest.json**, there is **no JS code inside** - i.e. there is no even technical possibility to steal your private data from Telegram webpage.

As Google rejected this extention due to Policy vioation (they don't allow to publish extensions with only functionaty to open 3rd party website) - the only option is to install it manually (see how-to below) 

## Video
[<img src="https://i.ytimg.com/vi/Q-CHQ58shWY/maxresdefault.jpg" width="50%">](https://youtu.be/Q-CHQ58shWY)

## How to install it in Chrome
- Clone the  repo
- Open ```chrome://extensions``` in chrome
- Toggle ```Developer mode```
- Load unpacked > choose ```src``` folder



