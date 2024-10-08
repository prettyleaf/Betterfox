![GitHub Maintained](https://img.shields.io/badge/open%20source-yes-orange)
![GitHub Maintained](https://img.shields.io/badge/modified%20-yes-g)
![GitHub Maintained](https://img.shields.io/badge/gets%20updates-yes-g)
![GitHub Maintained](https://img.shields.io/badge/maintained-yes-yellow)
[![Visitors](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fyokoffing%2FBetter-Fox&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=visitors&edge_flat=false)](https://hits.seeyoufarm.com)

# Betterfox
31% faster than regular Firefox<sup>[1](https://medium.com/@mihirgrand/comparing-popular-firefox-forks-6fa83fdfdaad#:~:text=31%25%20more%20than%20vanilla%20Firefox)</sup> :rocket:

[about:config](https://support.mozilla.org/en-US/kb/about-config-editor-firefox) tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/). 

:new: Now with [ESR support](https://github.com/yokoffing/Betterfox/tree/esr115#betterfox-esr).

## Required reading
*If you don't have it already: [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)*

0) Create a [backup profile](https://github.com/yokoffing/Betterfox/wiki/Backup).
1) Download the user.js file [here](https://raw.githubusercontent.com/prettyleaf/Betterfox/main/user.js) (Right click > `Save Link As…`).
2) Review [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and make any necessary changes.
   * See also [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) for other recommendations.
3) Open Firefox. In the URL bar, type `about:profiles` and press `Enter`.
4) For the profile you want to use (or use default), click `Open Folder` in the **Root Directory** section.
5) Close Firefox.
6) Move the `user.js` file into the folder.
7) Open Firefox and make changes in settings if you need.

*After restarting Firefox:*
1) Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with our [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2) Go to `C:\Program Files\Mozilla Firefox\distribution` and put [policies.json](https://raw.githubusercontent.com/prettyleaf/Betterfox/main/policies.json) there. 
3) Restart again and then check `about:policies`, if you see tweaks there, then you're good to go.
    * You probably don't have distribution, so create it.
    * If your Firefox folder isn't in that path, so find it yourself and do the same steps.

### **Optional**
0) Enable **DNS-level protection** with [NextDNS](https://nextdns.io/?from=xujj63g5). <sup><i>Use the link and support this page!</i></sup>
    * Check out our configuration [guide](https://github.com/yokoffing/NextDNS-Config) for the best experience.
    * See how to [quickly enable](https://support.mozilla.org/en-US/kb/dns-over-https) **secure DNS** in Firefox.

## Simple configs

`Fastfox`, `Securefox`, `Peskyfox`, and `Smoothfox` are guides to settings within Firefox.

The `user.js` — a configuration file that controls Firefox settings — is curated from these guides.

| List      | Description |
|:---------:|-------------|
| [Fastfox](https://github.com/yokoffing/Betterfox/blob/main/Fastfox.js)   | Increase Firefox's browsing speed. Give Chrome a run for its money!|
| [Securefox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js) | Protect user data without causing site breakage. |
| [Peskyfox](https://github.com/yokoffing/Betterfox/blob/main/Peskyfox.js)  | Provide a clean, distraction-free browsing experience. |
| [Smoothfox](https://github.com/yokoffing/Betterfox/blob/main/Smoothfox.js) | Get Edge-like smooth scrolling on your favorite browser — or choose something more your style. |
| [user.js](https://github.com/yokoffing/Betterfox/blob/main/user.js) | All the essentials. None of the breakage. This is your `user.js`. |

## Support

If you like the project, leave a :star: (top right) and become a [stargazer](https://github.com/yokoffing/Betterfox/stargazers)!

[![Stargazers repo roster for @yokoffing/Betterfox](https://reporoster.com/stars/dark/yokoffing/Betterfox)](https://github.com/yokoffing/Betterfox/stargazers)

<a href='https://ko-fi.com/Q5Q5G8EPH' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
<noscript><a href="https://liberapay.com/yokoffing/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

## Credit
* Modified by [pr3ttyleaf](https://twitch.tv/pr3ttyleaf) for everyday usage and perfomance. [Buy me a coffee.](https://www.donationalerts.com/r/pr3ttyleaf)
* Betterfox mirrors the ongoing work provided by [arkenfox](https://github.com/arkenfox/user.js). Additionally, this repository includes content reproduced or adapted from other sources. Credit for overlapping material goes to the original authors.
* Appreciation goes to the [Firefox](https://www.mozilla.org/en-US/firefox/new/) team and developers working on [Bugzilla](https://bugzilla.mozilla.org/home), fighting for the open web.
* A special thanks to [Alex Kontos](https://github.com/MrAlex94) of [Waterfox](https://github.com/WaterfoxCo/Waterfox) for his collaboration in v.116.
* Many thanks to the 2021 [Ghostery](https://github.com/ghostery) team for testing Betterfox at scale in its early days.

<div align='center'>
  <a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=19653&s=1' border='0' alt='Free Website Counter'></a><br / >
since 23 July 2022</div>
