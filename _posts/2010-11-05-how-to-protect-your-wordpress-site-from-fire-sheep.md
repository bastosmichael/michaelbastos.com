---
layout: post
title: Fire Sheep & your WordPress site
---

Many of you have read about Fire Sheep in the last few weeks since the ToorCon hacker’s conference. The program allows a novice want to be hacker to easily bring up cookie settings and be allowed to log into other people’s accounts within a local network and act as them online on any non SSL secured site. Basically if you’re in a coffee shop and you are using their free Wifi network, someone with the Fire Sheep plugin can login as you to your Facebook or any open session website online. To read more about how the program works please visit the link below for more information.

http://wiki.twit.tv/wiki/Security_Now_272

So how is this important for WordPress site owners? If you run a WordPress site, you most likely run a blog or business from it and are just as susceptible to this problem as any of the big companies like Amazon and others. If you are worried about your site’s security or the security of your users please use these tools to make your site more secure and give your users a safer experience on your site.  The first thing you will need to do is make sure that your webhost company provides SSL certificates or that they are willing to provide you the service. Then once you activate SSL you’ll need to create or use a paid for certificate so that the browsers know your site is safe. Once all that is done and it comes time for you to secure your website itself, the following plugins will really give you a head start in preventing the Fire Sheep problem on your site:

WPSSL (WordPress with SSL): http://wordpress.org/extend/plugins/wpssl/

This is a great plugin for you to use when you need to secure your WordPress users from the Fire Sheep problem. Once you install it you can choose which post or page you want to secure (aka an order form or contact page) by simply using the “force_ssl” under the Custom Fields section as a Name and putting a “true” value for it. There are ways of making sure that your site is SSL secure across the board but this is a good start to making sure your pages are HTTPS compatible.

Admin SSL: http://wordpress.org/extend/plugins/admin-ssl-secure-admin/

This plugin is more important for you and your backend users than just viewing a secure page, it secures your whole WordPress login experience and is a bit more complicated to install. This is great to prevent people from automatically logging into your site as one of your users or even as you the administrator.

There are other plugins that could be useful for preventing this problem but these two are the simplest implementations so far that I’ve found to fix this problem on WordPress. My hope is that sometime soon Automatic (the guys that make WordPress) will make this a focus of theirs and will make switching to SSL a serious part of the WordPress platform on both the pages and the logins. This is something the Web 2.0 and blogging community is not use to having to deal with but I see it as a positive for internet security, the more of a problem Fire Sheep becomes, the more it will force people to make their websites more secure and ensuring their users privacy is safer.
