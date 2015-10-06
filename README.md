# LimeChat

LimeChat is an IRC client for Mac OS X.

* One window for multiple servers.
* Rich keyboard shortcuts for your comfortable operations.
* Fast and stable.

## Author

* Satoshi Nakagawa http://github.com/psychs
* ##limechat on chat.freenode.net
* evil features by Squigger J Johnson

## "Evil" features
* Auto rejoin on kick
* Mass message
* Mass highlight
* Nickname ban evader
* Fake CTCP version reply
* Random name every launch
* Autojoin forced on added channels (helps ban evasion)
* CTCP dont respond
* DCC dont respond
* force join all saved channels
* hostname ban evader (disconnect, change hostname, nickname, and whatever else) (with fast reconnect)

note: To use the IP ban evader you have to set up n VPNs in the form "<VPN Name> #" ... currently it's hardcoded to 40 "CyberHost" VPNs but you can change the name and amount to anything you want in the code. Look at the ipEvade function in IRCClient.m. It probably won't even work probably without this set up properly or disabled. But not just AS-IS. Look at the code.


DONT HAVE, PLANNED:

* disconnect/reconnect spammer

IRC exploits not yet implemented

crapflooding - self explanatory

IP ban evader (disconnect, reconfigure VPN, reconnect, rejoin)

moderation mode challenger - join and leave with random names annoyingly

MESSAGE spammer.. just spam a ton of messages. somewhat annoying.

geolocate anyone via right click. (and maybe get the weather)

IP2Skype support… resolve people’s Skype

regular (slow) floods (channel/message…)


SHOUT OUTS TO 2600


## Thanks To

* Allan Odgaard  (WebViewAutoScroll and TextMate logo)
* Atsuhisa Shimazawa  (Badge images)
* Dustin Voss  (AsyncSocket)
* Eloy Duran  (RubyCocoa, crash reporter, Growl notifier, preferences patches)
* Evan Phoenix  (Inline images support)
* Fujimoto Hisa  (RubyCocoa)
* Josh Goebel  (CocoaSheet, many improvements on code and UIs)
* Jun Morimoto  (Bug fixes)
* Keiji Yoshimi  (Growl notifier patches, hot key patches)
* Kevin Ballard  (Theme support patches)
* Laurent Sansonetti  (RubyCocoa, many requests and suggestions)
* Peter Haza  (Channel name context menu patch)
* Python Software Foundation  (Python logo)
* Rails team  (Ruby on Rails logo)
* Shingo Morita  (Badge images)
* Stanley Rost  (Limelight theme)
* Stefan Rusterholz  (Many suggestions and patches)
* Takashi Tsugo  (Deep Ocean theme)
* The Growl Project  (Growl framework and logo)
* why the lucky stiff  (Syck)
* William Thimbleby  (Syck Cocoa)
* Yohei Endo  (Application icons)
* Yukihiro Matsumoto  (Ruby logo)

## License

LimeChat is copyrighted free software by Satoshi Nakagawa (psychs AT limechat DOT net).
You can redistribute it and/or modify it under the terms of [the GPL version 2](https://github.com/psychs/limechat/blob/master/GPL.txt).
