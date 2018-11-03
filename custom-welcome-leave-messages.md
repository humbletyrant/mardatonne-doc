---
description: Do you want to choose a better welcome/leave messages?
---

# Custom Welcome/Leave Messages

## _**`Welcomer`**_ module needs to be enabled!

This changes will only take effect if you have [welcomer](setting-up-welcomer.md) module enabled.

Please enable it first!

{% page-ref page="setting-up-welcomer.md" %}

### Custom definitions

```text
{{user}}        : Username
{{server}}      : Server name
{{membercount}} : Server member count
```

{% hint style="info" %}
You can include these in your message to get user/server's info
{% endhint %}

### How do i set messages?

#### Setting welcome message

Just run the following command:

```text
+setwm <custom welcome message>
```

{% hint style="success" %}
Once you get the confirmation message, you're ok!
{% endhint %}

![](.gitbook/assets/screenshot_20181103_194731.png)

#### Setting leave message

Just run the following command:

```text
+setlm <custom leave message>
```

{% hint style="success" %}
Once you get the confirmation message, you're ok!
{% endhint %}

![](.gitbook/assets/screenshot_20181103_195142.png)



