---
layout: post
title: How to send Telegram Messages from shell script
subtitle: Using the WhatsMate Telegram Gateway REST API
published: true
---

This article shows you how to send a Telegram message from a shell script.

Before the recipient can receive your Telegram message, she will need to register with the WhatsMate Telegram Gateway. Instructions are available on the [official site](http://www.whatsmate.net/telegram-gateway-api.html). *Unregistered users will NEVER receive messages from the Gateway.*


To send a Telegram message from a shell script, do this:

1. Copy the following source code to your script.  <script src="https://gist.github.com/whatsmate/c7831b94ff7a97e52f9fe4459e502d2f.js"></script>
2. Specify your target recipient on line 9. Remember to include the country code.
3. Specify your message on line 10.
4. Make your script executable: `chmod 755 send-telegram.sh`
5. Run the script to send your message: `./send-telegram.sh`


The trial account allows you to send up to 50 messages per day for the first 1000 messages. [Upgrade to the Premium Account](http://www.whatsmate.net/telegram-gateway-subscribe.html) to send unlimited number of messages.

