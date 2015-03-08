---
author: stevegio
comments: true
date: 2010-11-30 02:29:03+00:00
layout: post
slug: airprint-configured-first-impressions
title: AirPrint Configured. First Impressions.
wordpress_id: 29
categories:
- tech
post_format:
- None
---

Over the long weekend my three year old Canon printer gave up the ghost. Some kind of power supply problem. Normally I would be upset but the event simply gave me a perfect excuse to buy a new printer. Since I recently updated all my iOS devices to 4.2, that new printer would be one that supports ePrint which would let me print from my recently updated iPhone or iPad.
I found the [iOS: AirPrint 101](http://support.apple.com/kb/HT4356) doc from Apple very helpful.  It told me _exactly_ what printers supported AirPrint. Be forewarned. Not all ePrint compatible printers support AirPrint. Stick to the list supplied by Apple. I settled on the [HP PHOTOSMART PLUS e-All-IN-ONE B210](http://h10010.www1.hp.com/wwpc/us/en/sm/WF05a/18972-18972-238444-421635-410635-4021933.html). It not only supported ePrint but wifi, decent photo printing, and scanning. It's perfect for a home printer.
Configuring the printer hardware took about 5 minutes. Nothing out of the ordinary. The printer chugged along, cycling through diagnostics, finally prompting me to configure the wireless connection. Once that was complete, the printer emitted a diagnostic page with some information about the ePrint setup. (More about this below.) On each of my Mac OS X machines I installed the drivers, added the printer, and printed a test page or two. Each worked fine.
There is nothing to install on your iOS devices to take advantage of AirPrint. You just need to update to iOS 4.2 and AirPrint should just work. I used the aforementioned AirPrint 101 doc as a guide. My tests with the standar apps (Mail and Safari) were fine and went as advertised. I was also able to view the print queue right from my iOS device by double pressing the home button and tapping on the AirPrint "app" running in the multitasking area of the iPhone and iPad. Everything just worked. The only disappointing bit was printing from Pages. That didn't work or at least there was no print button off the share button. I also tried Numbers and Keynote. No joy there as well. I have updated the apps recently so I'm not sure when these apps will have the print button. I would think Apple would have included this in the last update. 
There is a workaround for apps that don't have the print button. The ePrint configuration on the HP printer creates a special, Internet accessible, email address. It looks something like `asdf123asdf@hpeprint.com`. If you email documents to that email address it will print on your printer.  It's a great feature but you need to make sure you lock down just what email addresses can send to your printer. Anyone that knows the email address can print to your ePrint printer. As a safety measure, HP allows you to restrict what email addresses can send jobs to the printer. This setup is pretty simple and the instructions are printed on that first page the printer prints at the end of the hardware setup. I tested this from Numbers and it worked fine. A bit annoying but it's functional.
Overall I'm quite happy with AirPrint so far.  The HP printer works great.  Apps that support Airprint work flawlessly. While I'm waiting for the rest of the apps I care to print from to support it, I can use the standard ePrint via email. But like all things iOS this is just going to get better as time passes. Pretty magical, eh?
