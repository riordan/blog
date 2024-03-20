---
title: 'How to connect to the LinkNYC private network without an Apple device'
description: 'Non-Apple users deserve private, secure Wi-Fi too. Here's how to do it from a Linux desktop/laptop.'
pubDate: '2024-02-06'
heroImage: '/blog-placeholder-1.jpg'
---

If you've spent time out and about in NYC, you've probably seen one of the towering LinkNYC monoliths, beaming high-speed Wi-Fi signals, in exchange for showing an ever-changing set of ads (and local neighborhood information in the ad spots they didn't sell). Like most public Wi-Fi networks, each time you connect to the `LinkNYC` network, you're stuck waiting for a "captive portal" webpage that promises internet access in exchange for signing over your privacy rights and email address. Thanks to the technical complexities of allowing a device to connect, but forcing it to go to that one captive portal site, while blocking all other sites, you might never get to the captive portal. And each time you reconnect, you're stuck hoping that captive portal will once again show up before you can once again sign your rights away. 

However, there is a mythical `LinkNYC Private` network, one that allows its users to automatically connect, no email address webpage needed, and comes with the benefit of encrypting your traffic (between your computer and the kiosk; [no telling where it goes after that](https://theintercept.com/2018/09/08/linknyc-free-wifi-kiosks/)). LinkNYC advertises that its private network is only available for iPhones and iPads, and it's pretty tough to find the part of their site that'll set this up for you.

> PS: If you are on an iPhone, iPad, or Mac, [clicking the `Download Private Network Profile` button](https://www.link.nyc/faq.html#private-profile-download) on this page while using Safari will download a mobileconfig.profile file. By going into Settings, you'll be asked to enable the LinkNYC Private profile, you'll be able to automatically connect to the LinkNYC private network. That said, you **absolutely** [should not trust random mobileconfig files](https://www.howtogeek.com/176195/why-configuration-profiles-can-be-as-dangerous-as-malware-on-iphones-and-ipads/); they've got the power to lock you out of your own device, to route all your traffic to malicious places, real fun stuff.

Last year, I decided I'd switch my primary laptop over to Linux (first [Manjaro](https://manjaro.org), then [Ubuntu](https://ubuntu.com), then back to Manjaro) and was shocked to find I was no longer able to connect to `LinkNYC Private` with my standard OS Wi-Fi connection tools.

## Here's how you connect to LinkNYC Private network on most Linux desktops

Last year, when I switched my primary l




## Wait, why can't I just use the normal Wi-Fi?
