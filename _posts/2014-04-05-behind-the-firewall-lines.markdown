---
layout: post
title:  "Behind the firewall lines - Internet firewalls"
date:   2014-04-05 09:10:00
categories: post
---

> " Hey, Did you see the new \_\_\_\_\_\_\_.com site? You can \_\_\_\_\_\_\_ in the site!! "

> " Wow! Looks cool, Let me check... Shit, "

> ***Firewall Blocked - Content blocked as per internet access policy***

I often come across this conversation when i was in college and in my workplace. Almost every IT employee and everyone who does his work through computer often experience this situation. 

Let me share my point of view about the internet firewalls I've faced.

###Ok for school or college.

School or College is the time where most of the people are introduced to Internet and its been introduced as an Entertainment medium. Even after using internet for more than a year only I came to know that its also a better place for learning more than books. If there is no firewall, more that 90% will be using it for the sole purpose of entertainment. May be only 10% will use it for learning and with the firewall is being set up with the blocking categories, Its likely less that 1% is going to see a block for learning because of the firewall. 

When I was in college, Streaming media and Social networking was the website categories that was blocked on weekdays and open on weekends. Its ok, I can bookmark the youtube likns and wait for another 4 days max for a learning video. And when I was eager to learn and develop a facebook app, It was blocked and I had to learn and work on weekends for the FB app. 

> " It is ok to put a firewall for students and to sacrifice the extra learning of 1% for the good of 90%. "

The firewall they used was not that great, it was blocking some learning sites, miscategorizing websites. But they had an intranet webtool called 'shoutbox' where we can post the links which was blocked mistakenly by the firewall; And the websites will be reviewed and whitelisted the next day.

>" The environment thats a perfect fit for better work and productivity differs for everyone. "

I don't listen to songs. I'll be more productive when I watch some action movies or crime serials while coding. Yeah, It'll be in a small always-on-top player window. In college days, there was no problem as I had used my own laptop. My brain used to work well on programming logics if a video is playing in a overlay window.

###Even for workplace?, that doesn't make sense.

When I joined an IT firm as a Software Engineer, It was shoking to see a firewall that was put up for the internet access. Students is a stage where we often change our life goals and desired as we get distracted on what we see. But when we joins a job and becomes and employee, We've set our path. There is no use of having a internet firewall to straighten our path. 

Sure, The office needs to have some internal security measures to secure their private data. But atleast have some firewall which doesn't block the learning and knowledge growth. Moreover almost everyone have a smartphone connected with internet.

> A: " Hey, did you see the photo \_\_\_\_\_\_\_ just uploaded in facebook? "

> B: " What?! Don't you have firewall in your PC? "

> A: " Don't you have a smartphone?! Grow up. "

The impact on firewall for productivity becomes very less if we have a smartphone with internet connectiviry. As an employee, I need to have some freedom to work productively.

###Blocked.. blocked.. blocked..

In the 2 years of working with the company, approx. 5 or 6 different firewall rules or firewall softwares was deployed. And every time the firewall changes, I've to change my browsing habits, resetting bookmarks, finding alternate sites, find some workaround to get blocked contents etc etc... 

> " Hey, Shall we try a new automation for our product? "

> " Nah.. It'll be blocked in firewall to download the required tools. Let it be. " 

Even the [Google CDN](https://developers.google.com/speed/libraries/devguide) with 'http' is blocked (only https works), so the websites using [jQuery](http://jquery.com/) from Google CDN won't work. Some [URL shortners](http://en.wikipedia.org/wiki/URL_shortening) are blocked. On top of all, the website category 'Uncategorised' is blocked. Yes, the new websites and the websites for which the firewall couldn't able to categorize all blocked. Every new websites and web tools which i see in Hacker News is blocked. If i see 'Show HN', I know it will be blocked. 

Also I have [Google Chrome](https://www.google.com/intl/en/chrome/browser/), but installing extension is blocked!!. In subsequent firewall rule changes, Google Reader was opened, closed, opened, closed.. then [Google closed it completely](http://www.google.com/reader/about/). Then I've moved to [Digg Reader](http://digg.com/reader), but then as Google CDN blocked, it didn't work anymore as it uses jQuery from there.

Then a new software was put up in all our systems to track when & how long each and every applications were running; A report of how long we were doing development/corporate/personnal works will e generated.

> " Longer working hours &ne; Higher productivity ; Isn't it? "

But still a great thanks for the firewall for not blocking [Twitter](http://twitter.com), [Github](http://github.com), [Hacker News](http://news.ycombinator.com) ( hacker news once got blocked as hacking category, but then it worked ).

###The only good thing of being firewalled.

Being trapped in a firewalled internet, everyone tries to find some tricks to beat the firewall and learn some things in the process. In the college days, I got to know about proxy sites and some networking behind it. I learned about tunneling and to use VPS to tunnel and get away from firewall.

Then working in a company, the learning was even more in the process of finding a way out of the firewall. The first firewall was allowing new proxy sites and after some days the site will be blocked. Yes, Its easy to find new proxy sites through twitter. But every time a site is blocked, I had to open up the proxy site, copy & paste the url, hit enter and I felt lazy for that.

Googling said some chrome extensions are there. But installing chrome extensions also blocked. So I've learned about [Chrome Extention Development](http://developer.chrome.com/extensions/getstarted.html), and did a small extension which opens the blocked page in a proxy site. 

> " Wow! Chrome/Firefox extension development is not much tougher as I thought. 

> Its just JavaScript!! " 

Then did some extensions for google bookmark, twitter share, add the blocked URL to pocket, take screenshot of blocked webpage through online tools, an extension to hide images from the website and show only text content ( Its office right, I can't be seen browsing a site with some strange images ). We can customize the design of any website in the way we want with a small extension if you know [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) & [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS).

The customization I did includes A black themed google, A full screen twitter and some minor changes I wanted in some websites. Even when twitter made images shown by default in the timeline, I'd just made it hidden.

I wouldn't know about Read it later apps or learned about chrome extension development if the firewall was not there.

###Escape plan :)

Here is some methods that I've used to jump across the firewall that may be useful for you,

**Proxy sites ( If firewall is so week )**<br/>
[http://hidemyass.com](http://hidemyass.com)<br/>
[http://kproxy.com](http://kproxy.com)<br/>
[List of new proxy sites](http://twitter.com/proxysites)<br/>

**Read it later apps**<br/>
[http://getpocket.com](http://getpocket.com)<br/>
[http://instapaper.com](http://instapaper.com)<br/>
[http://readability.com](http://readability.com)<br/>

**Webpage screenshot tools**<br/>
[http://web-capture.net](http://web-capture.net)<br/>
[http://url2png.com](http://url2png.com)<br/>
[http://ctrlq.org/screenshots](http://ctrlq.org/screenshots)<br/>

**Cached contents**<br/>
[Google cached version of webpage](http://webapps.stackexchange.com/questions/15633/how-to-modify-a-url-to-get-a-google-cached-version-of-page)<br/>
[http://archive.org/web](http://archive.org/web)<br/>

**Tunneling ( If you own a  VPS )**<br/>
[How to setup ssh tunneling on a VPS](https://www.digitalocean.com/community/articles/how-to-set-up-ssh-tunneling-on-a-vps)<br/>

and may be more that i don't know of..

###Conclusion

In my point of view, at least there is some use of placing a firewall in the school or college network, but when it comes to workplace, there is no use of it as everyone has a smartphone and the firewall becomes just another blocking wall for learning.

Anyway I've moved out of my previous MNC for our own start-up.

>" Yay! No firewalls now. "

The productivity becomes much much more without a firewall. 
