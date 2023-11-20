<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# chatGPT-web for YunoHost

[![Integration level](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://dash.yunohost.org/appci/app/chatgpt-web) ![Working status](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Install chatGPT-web with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install chatGPT-web quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

ChatGPT-web is a simple one-page web interface to the OpenAI ChatGPT API. To use it, you need to register for an OpenAI API key first. All messages are stored in your browser's local storage, so everything is private. You can also close the browser tab and come back later to continue the conversation.

### Features

- Private: All chats and messages are stored in your browser's local storage, so everything is private.
- Customizable: You can customize the prompt, the temperature, and other model settings. Multiple models (including GTP-4) are supported.
- Cheaper: ChatGPT-web uses the commercial OpenAI API, so it's much cheaper than a ChatGPT Plus subscription.
- Fast: ChatGPT-web is a single-page web app, so it's fast and responsive.
- Mobile-friendly: ChatGPT-web is mobile-friendly, so you can use it on your phone.
- Voice input: ChatGPT-web supports voice input, so you can talk to ChatGPT. It will also talk back to you.
- Pre-selected prompts: ChatGPT-web comes with a list of pre-selected prompts, so you can get started quickly.
- Export: ChatGPT-web can export chats as a Markdown file, so you can share them with others.
- Code: ChatGPT-web recognizes and highlights code blocks and allows you to copy them with one click.


**Shipped version:** 2023.11.20~ynh1

**Demo:** https://niek.github.io/chatgpt-web/

## Screenshots

![Screenshot of chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Antifeatures

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentation and resources

* Official app website: <https://niek.github.io/chatgpt-web/>
* Upstream app code repository: <https://github.com/Niek/chatgpt-web>
* YunoHost Store: <https://apps.yunohost.org/app/chatgpt-web>
* Report a bug: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
or
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
