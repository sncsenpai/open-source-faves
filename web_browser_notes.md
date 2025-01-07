# Web Browser Notes

Like some others, I use multiple devices outside of any "walled-garden" ecosystems. So, I work between macOS, Windows, Linux, and Android (sorry, no iOS or iPadOS). 

With that in mind I spent a long while looking for alternative browsers that are cross-platform, free from tracking and privacy invasion, allows me to sync up between those devices, and is open source. 

I have collated all my notes into one places and sharing them in case you're interested or if you find it useful. It was a real eye-opening experience for me.

## Proprietary Desktop Browsers

- [Google Chrome](https://www.google.com/chrome/)
- [Microsoft Edge](https://www.microsoft.com/edge)
- [Apple Safari](https://www.apple.com/safari/)
- [Opera](https://www.opera.com/)
- [Opera GX](https://www.opera.com/gx)
  - Gaming-oriented version of Opera.
- [Vivaldi](https://vivaldi.com/)
- [DuckDuckGo Privacy Browser](https://duckduckgo.com/app) 
  - Partially open source
- [Arc](https://arc.net/)
- [Comodo](https://browser.comodo.com/)
  - Comodo Dragon (Chromium) and IceDragon (Firefox)

## Open Source Desktop Browsers

The categorisation of the Firefox forks can be a little misleading, so I'm going a little lower level than expected. Modern Firefox ESR releases are not using the Gecko engine, which has roots in the original Netscape Communication suite that was open sourced by AOL.[^1] Goanna-based browsers were forked from Gecko before Mozilla deprecated it, and both are maintained separately.

- [Firefox](https://getfirefox.com/)-based
- [Chromium](https://www.chromium.org/Home/)-based
- [Goanna](https://www.palemoon.org/tech/goanna.shtml)-based
  - Forked from an earlier build of Gecko and maintained separately[^2]  [^3]
- [SeaMonkey](https://www.seamonkey-project.org/)
  - Open source successor of the Netscape/Mozilla suite[^4] and built on the Gecko engine.

### Chromium-based

- [Brave](https://brave.com/)
- [Iridium](https://iridiumbrowser.de/)
- [ungoogled chromium](https://github.com/ungoogled-software/ungoogled-chromium)
  - Compared to the proprietary forks, this takes a lightweight approach to removing Google dependencies.


### Firefox-based

- [Tor Browser](https://www.torproject.org/download/)
- [Firefox Focus](https://www.mozilla.org/firefox/browsers/mobile/focus/)
- [LibreWolf](https://librewolf.net/)
- [Waterfox](https://www.waterfox.net/)
- [Zen Browser](https://zen-browser.app/)
- [Mullvad Browser](https://mullvad.net/en/browser)
  - based on Tor Browser
- [Floorp](https://floorp.app/)

### Goanna-based

- [Pale Moon](https://www.palemoon.org/)
- [Basilisk](https://basilisk-browser.org/)
- [K-Meleon](http://kmeleonbrowser.org/)
  - Has not been updated in a while

## Mobile Browsers

### Proprietary
- [Amazon Silk](https://docs.aws.amazon.com/silk/latest/developerguide/what-is-silk.html)
- [Apple Safari](https://support.apple.com/en-gb/guide/iphone/iph1fbef4daa/ios)
- [Arc](https://arc.net/search)
- [Dolphin](https://dolphin.com/)
- [Google Chrome](https://www.google.com/chrome/)
- [Microsoft Edge](https://support.microsoft.com/microsoft-edge)
- [Opera Mobile](https://www.opera.com/browsers)
- [Puffin Browser](https://www.puffin.com/) [^concerns]
- [Vivaldi](https://vivaldi.com/)
- [UC Browser](https://www.ucweb.com/) [^concerns]
- [Samsung Internet](https://www.samsung.com/us/support/owners/app/samsung-internet)
- [QQ browser](https://browser.qq.com/)  [^concerns]

### Open Source

- [Brave](https://brave.com/)
- [Firefox Focus](https://www.mozilla.org/firefox/browsers/mobile/focus/)
- [Mozilla Firefox](https://www.mozilla.org/firefox/browsers/mobile/)
- [Waterfox](https://www.waterfox.net/docs/releases/G6.0.8/#_top)

## Browsers I'm not sure of

- [Maxthon](https://www.maxthon.com/) 
  - Chromium-based
  - Proprietary
  - Hong Kong company headquartered Singapore
  - Historical issues surrounding data privacy[^5]
- Purposely ignoring other platform specific browsers, such as:
  - [Falkon](https://www.falkon.org/) which is Linux-based.
  - [UC Browser](https://ucweb.com/)
    - Only for Android devices
    - **WARNING**: Should be avoided. See [citizenlab.ca](https://citizenlab.ca/2016/08/a-tough-nut-to-crack-look-privacy-and-security-issues-with-uc-browser/) for more info
  - [Samsung Internet](https://www.samsung.com/uk/apps/samsung-internet/)
    - Only for Android devices
  - [GNUzilla and IceCat](https://www.gnu.org/software/gnuzilla/)
    - For Linux systems
- [Epic Browser](https://epicbrowser.com/)
  - Moved from Firefox to Chromium base
  - Features specific to Indian users
    - Same concern also applies to JioPages/JioSphere[^6]
- [Puffin Secure Browser](https://www.puffin.com/secure-browser)
  - Chromium-based
  - Traffic passes through Puffin servers and pages rendered through the remote browser, but they do indicate a no-log policy
- [Yandex Browser](https://browser.yandex.com/)
  - Chromium-based
  - Association to Russia is a sensitive area and there have been legal issues in this regard[^7]
- [UC Browser](https://www.ucweb.com/) has a history of privacy and security concerns. 
  - Traffic passes though the company's servers.
  - See [Wikipedia](https://en.wikipedia.org/wiki/UC_Browser#Privacy_and_security_vulnerabilities) for a summary of issues.

## Privacy Stuff

If, like me, you're not happy with the idea of "Surveillance Capitalism", in the sense that you don't mind ads but do mind that they track you, the choice of browser would be the first step. Then you would want to consider further steps to protect your privacy with browser extensions and testing your browser config.

> **IMPORTANT:** Minimise usage of browser extensions to mitigate unique browser fingerprinting. 

### Browser Extensions

- [Decentraleyes](https://decentraleyes.org/) [^Firefox Add-on] [^Firefox Mobile] [^Chrome Extension] [^Pale Moon Extension] [^Opera Extension] [^MS Edge Extension]
- [Privacy Badger](https://privacybadger.org/) [^Firefox Add-on] [^Firefox Mobile] [^Chrome Extension] [^Opera Extension] [^MS Edge Extension]
- [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) [^Firefox Add-on] [^Firefox Mobile] [^Opera Extension] [^MS Edge Extension] [^8]
- [Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/) [^Firefox Add-on] [^Firefox Mobile] [^Chrome Extension] [^MS Edge Extension]

### Privacy Tools

- [EFF: Cover Your Tracks](https://coveryourtracks.eff.org/) - Test your browser to see how well you are protected from tracking and fingerprinting
- [Decentraleyes Testing Utility](https://decentraleyes.org/test/) - Test your level of protection
- [PrivacyTests.org](https://privacytests.org/) - Open-source tests of web browser privacy.
- [Privacy Guides #Desktop Browsers](https://www.privacyguides.org/en/desktop-browsers/)
  > We recommend [Mullvad Browser](https://www.privacyguides.org/en/desktop-browsers/#mullvad-browser) if you are focused on strong privacy protections and anti-fingerprinting out of the box, [Firefox](https://www.privacyguides.org/en/desktop-browsers/#firefox) for casual internet browsers looking for a good alternative to Google Chrome, and [Brave](https://www.privacyguides.org/en/desktop-browsers/#brave) if you need Chromium browser compatibility.

-----

[^1]: Wikipedia: [Netscape Communicator](https://en.wikipedia.org/wiki/Netscape_Communicator)
[^2]: [Introducing: Goanna](https://forum.palemoon.org/viewtopic.php?f=1&t=8607)
[^3]: Pale Moon Forum: [What are the differences with Firefox?](https://forum.palemoon.org/viewtopic.php?f=24&t=139#p461)
[^4]: Wikipedia: [Mozilla Application Suite](https://en.wikipedia.org/wiki/Mozilla_Application_Suite)
[^5]: SecurityWeek: [Maxthon Browser Sends Sensitive Data to China](https://www.securityweek.com/maxthon-browser-sends-sensitive-data-china/)
[^6]: https://www.jio.com/jcms/apps/jiosphere/
[^7]: Wikipedia: [Yandex#Legal issues](https://en.wikipedia.org/wiki/Yandex#Legal_issues)
[^8]: [This extension may soon no longer be supported on Chrome](https://github.com/uBlockOrigin/uBlock-issues/wiki/About-Google-Chrome's-%22This-extension-may-soon-no-longer-be-supported%22)
[^concerns]: See [Browsers I'm not sure of](#browsers-im-not-sure-of)
[^Firefox Add-on]: Add-on available on Firefox
[^Chrome Extension]: Extension available in [Chrome Web Store](https://chrome.google.com/webstore/category/extensions) for Chromium variants
[^Opera Extension]: Extension available in [Opera store](https://addons.opera.com/)
[^MS Edge Extension]: Extension available in [Microsoft Edge store](https://microsoftedge.microsoft.com/)
[^Pale Moon Extension]: Extension available for Pale Moon via [Add-ons Site](https://addons.palemoon.org/extensions/)
[^Firefox Mobile]: Also available on [Firefox for Android](https://addons.mozilla.org/en-GB/android/)
