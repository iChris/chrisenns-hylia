---
title: 'Site Was Hacked Last Night'
date: 2013-03-19
draft: false
tags: [hacked, Uncategorized, wordpress]

---

https://twitter.com/claybitner/status/314033569272053760

* * *

My apologies if you saw a couple of posts about financial news last night on the site or via RSS - somehow a person/bot created a user account on my blog with administrator privileges and posted a couple of articles. I haven't figured out anything else they might have done but I will be [scanning the site](http://sucuri.net) throughout the day and watching for anything else odd. The place I noticed an odd setting was under Settings -> General (/wp-admin/options-general.php on your WordPress install): **How My Install Was Configured:** ![WordPress Settings Anyone Can Register](https://chrisenns.com/wp-content/uploads/2013/03/Screen-Shot-2013-03-19-at-9.48.40-AM.png) **How It Should Be Configured:** ![WordPress Settings Anyone Can Register](https://chrisenns.com/wp-content/uploads/2013/03/Screen-Shot-2013-03-19-at-9.48.33-AM.png) I don't think I set it up the way it was with anyone being able to register AND be given Administrator access - but I have had this blog running for a long time so maybe I did at one point and forgot to turn it off. Or maybe there's a backdoor somewhere in one of my plugins? [Sucuri](http://sucuri.net) didn't turn anything up but like I said, I'll keep scanning throughout the day. Thanks to [@claybitner](https://twitter.com/claybitner/status/314033569272053760) for pointing it out to me this morning.