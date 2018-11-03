---
description: Here we'll guide you installing logger..
---

# Setting up logger

## What is module **`logger`**?

Logger is a good module that will log everything happens in your server. For example if someone changes username, it logs. If someone creates a role, it logs.

### When does it log?

* If someone edits a message
* If someone updates name of the channel
* If someone changes nickname
* If someone updates server name
* If someone updates a role
* If someone updates an emoji
* If someone creates a channel
* If someone deletes a message
* If someone deletes a channel
* If someone creates an emoji
* If someone deletes an emoji
* If someone creates a role
* If someone deletes a role
* If someone updates a role
* If someone uses `+purge` command

### This module works in sync with _**`swearFilter`**_ module.

This also can get info from _**`swearFilter`**_ module and logs message that contains bad word.

### How do i enable it?

Just run the following command:

```text
+setlogger <logger channel name>
```

{% hint style="info" %}
 Please note that bot needs to have the permissions to send messages to the logger channel.
{% endhint %}

Once you get the confirmation message, you're ok!

![Confirmation message](.gitbook/assets/screenshot_20181103_184434.png)



