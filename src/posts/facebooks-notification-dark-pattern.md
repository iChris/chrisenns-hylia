---
title: 'Facebook''s Notification Dark Pattern'
date: 2016-11-21
draft: false
tags: [dark pattern, facebook, ios, iOS Apps, notifications, Technology, ui]

---

_If you're not familiar with dark patterns in web/app design, [Ars Technica has a good primer](http://arstechnica.com/security/2016/07/dark-patterns-are-designed-to-trick-you-and-theyre-all-over-the-web/) with one of the people maintaining a library of dark patterns at the appropriately named [DarkPatterns.org](http://darkpatterns.org)._ In Facebook's Messenger app for iOS, you can choose to allow the app to use iOS' notification system to let you know when you have a new message. Simple enough. Personally I prefer to not have most apps send banners/alerts \[footnote\]iMessage/Messages and certain emails being the notable exception to my rule.\[/footnote\] and just badge the app icon with a number when there's something to see. So this is how I have Facebook Messenger set up in iOS' notifications settings: ![img_9948](/wpblog/wp-content/uploads/2016/11/IMG_9948.png) So my settings are as follows:

*   Show in Notification Center is off
*   Sounds are off
*   Badge App Icon is on
*   Show on Lock Screen is off
*   And nothing is allowed to show when my iPhone is locked

But if I look at Facebook Messenger's settings screen for app specific notifications, it shows me this: ![Facebook Messenger Notification Settings](/wpblog/wp-content/uploads/2016/11/IMG_9947.png) There's a red exclamation mark indicating something is wrong with my Notification Settings. The copy below it implies that Facebook Messenger isn't allowed to use iOS' notification system.

> Turn on notifications to get messages faster - even when you're not in the app

But the iOS notifications setting screen, shown above, show that Facebook Messenger **does** have access to the iOS notifications system - I just don't have it set up _the way_ Facebook wants me to. I initially thought I had done something wrong with how I had it configured. It's worth mentioning: in the list of devious things Facebook does to try and get you to use their apps more, this is pretty low on the list in terms of evil rating. But it demonstrates to me how "confusing the user to get them to do what we want" is very much on the table at Facebook when it comes to how they design their apps.