---
layout: page
title: Jabber
aliases:
    - /en/service/xmpp.html
menu_group: service
translationKey: 405fa099b89ec281d5df6c1eea477213
icon: xmpp.svg
description: Open instant messaging alternative to Whatsapp and co.
links:
    web:
        url: "https://www.systemli.org/jabber"
        text: "Web-Jabber"
    messengers:
        url: "https://wiki.systemli.org/howto/jabber-ubersicht"
        text: "Overview of Jabber messengers"
    pidgin:
        url: "https://wiki.systemli.org/howto/jabber"
        text: "How-To: Jabber and Pidgin"
---

**Our Jabber server will be [shutdown](https://www.systemli.org/en/2023/02/06/shutdown-of-jabber.systemli.org-on-08/31/2023/) on 08/31/2023. Registration of new accounts is not possible anymore.**

Jabber (also called XMPP) is an instant messaging-, respectively chat-service and therefore an alternative to Facebook-chat, ICQ, MSN or similar services. Since many years we offer a Jabber-server (jabber.systemli.org).

Contrary to the services mentioned above, we neither retain your contents nor your connection data.

To set up a connection to our server, you need a chat program. For using Jabber, there are different ones. For example [Gajim](https://gajim.org/) (Windows/Linux), [Monal](https://itunes.apple.com/us/app/monal-free-xmpp-chat/id1060957067?mt=12) (OS X), [ChatSecure](https://chatsecure.org) (iOS) oder [Conversations](https://conversations.im) (Android).

We recommend using a program on your computer. If this is not possible (for example at university or at work), use our [Web-Jabber](https://www.systemli.org/jabber).

## Connection data

```
Server:   jabber.systemli.org
Port:     5222 (STARTTLS)
Bosh-URL: https://www.systemli.org/jabber/bosh
```

### Onion Service Address

```
razpihro3mgydaiykvxwa44l57opvktqeqfrsg3vvwtmvr2srbkcihyd.onion
```

## Using Jabber

When using jabber.systemli.org, please consider the following:

* **Use additional encryption: OMEMO, OTR or GnuPG.**
* **Disable logging in your Jabber client.**
* Support your friends in disabling logging and using additional encryption.
* Please follow our [instructions (for Pidgin)](https://wiki.systemli.org/howto/jabber_eng).
* **Inactive accounts will be automatically deactivated after one year.**
* The content of group chats is ephemeral and will get lost in case of server reboots.
* Transmission of big files to acccounts on other servers might be unencrypted.


[![](/assets/img/messaging.one-badge.svg)](https://check.messaging.one/result.php?domain=jabber.systemli.org&amp;type=client)
