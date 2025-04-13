# personal-blocklist

## AdGuard Home or AdGuard for Android DNS Filtering

- AdGuard DNS Filter (Enabled by default)

- [HaGeZi Pro Plus](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)

- [HaGeZi Threat Intelligence Feeds](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)

- [Abused TLDs - for local phishing](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt)

- [HaGeZi Native Tracker (Depending on Device)](https://github.com/hagezi/dns-blocklists?tab=readme-ov-file#native)

- [WindowsSpyBlocker Update - For disabling windows update, but blocks access to microsoft store](https://github.com/crazy-max/WindowsSpyBlocker/raw/master/data/dnscrypt/update.txt)

- [Adobe Tracker Blocklist (if you use adobe products)](https://a.dove.isdumb.one/list.txt)

- [Custom Filter (blocks tor2web, disable IDN homographs (non-latin domains and TLDs), unblocking important domain)](https://raw.githubusercontent.com/arfshl/personal-blocklist/refs/heads/main/internal-usage/b.txt)

#### Parental Control

- You Can Block/Unblock Services at Blocked Services menu, and set schedule for pause blocking

- [HaGeZi Gambling](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/gambling.txt)

- [NextDNS Gambling](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/gambling.txt)

- [ABPindo Adult](https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/aghome_adult.txt)

- [personal-blocklist anti-gambling (Experimental)](https://github.com/arfshl/personal-blocklist/raw/main/my-filter/antijudol.txt)

- [HaGeZi NSFW](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nsfw.txt)

- [NextDNS Porn](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/porn.txt)

- [Safesearch Enforcing](https://github.com/AdguardTeam/HostlistsRegistry/raw/refs/heads/main/assets/engines_safe_search.txt)

- [YouTube Strict Mode](https://raw.githubusercontent.com/AdguardTeam/HostlistsRegistry/refs/heads/main/assets/youtube_safe_search.txt)

- [HaGeZi Safesearch Not Supported](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/nosafesearch.txt)

- [NextDNS No Safesearch](https://raw.githubusercontent.com/nextdns/no-safesearch/refs/heads/main/domains)

- [HaGeZi Piracy](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/anti.piracy.txt)

- [NextDNS Piracy](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/piracy.txt)

- [NextDNS Dating](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/dating.txt)

- [ShadowWhisperer's Dating List](https://raw.githubusercontent.com/ShadowWhisperer/BlockLists/master/Lists/Dating)

- [NextDNS Gaming](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/gaming.txt)

- [NextDNS Social Networks](https://github.com/arfshl/nextdns-blocklists/raw/latest/subscriptions/social-networks.txt)

## uBlock Origin | Brave Browser | AdGuard for Android

- Enable Aggressive Mode for Brave browser 

- Keep Default List, Enable Easylist Social, Easylist Annoyances / Fanboy Annoyances, uBlock Annoyances (uBlock Origin only)

- Make sure ABPindo is enabled (For indonesian region)

- [HaGeZi Threat Intelligence Feeds](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)

- [Abused TLDs - for local phishing](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds-ublock.txt)

- [AdBlockID](https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/realodix/AdBlockID@master/dist/adblockid.adfl.txt&title=AdBlockID)

- [🚪 Browse websites without logging in](https://raw.githubusercontent.com/DandelionSprout/adfilt/refs/heads/master/BrowseWebsitesWithoutLoggingIn.txt)


## NextDNS Configuration

## AdGuard DNS Configuration


## Recommended AdGuard Home/AdGuard for Android encrypted DNS Upstream

| Provider | DNS-Over-HTTPS/HTTP3 | Alternative UDP Port (for fallback/bootstrap) |
| --- | --- | --- | 
| Cloudflare DNS | https://cloudflare-dns.com/dns-query |
| Cloudflare DNS - Security | https://security.cloudflare-dns.com/dns-query |
| Quad9 (Anti-malware) | https://dns.quad9.net/dns-query | 9.9.9.9:9953, 149.112.112.112:9953
| NextDNS | https://dns.nextdns.io/dns-query | 45.90.28.0:5353, 45.90.30.0:5353
| AdGuard DNS Unfiltered (Default) | https://unfiltered.adguard-dns.com/dns-query | 94.140.14.140:5353, 94.140.14.141:5353 |
| ControlD Unfiltered | https://freedns.controld.com/p0 |
| ControlD Malware | https://freedns.controld.com/p1 |
| ControlD Uncensored | https://freedns.controld.com/uncensored |
| Mullvad | https://dns.mullvad.net/dns-query |
| dns0.eu | https://dns0.eu |
| dns0.eu ZERO (Anti-malware) | https://zero.dns0.eu 
## Android/iOS Secure DNS with Adblocking
Criteria: Must be have Ads, Tracker and Malware blocking capabilities

| Provider | Address | Apple Mobileconfig
| --- | --- | --- |
| ControlD Hagezi's DNS - Pro| x-hagezi-pro.freedns.controld.com | [Apple](https://api.controld.com/mobileconfig/x-hagezi-proplus?type=free&exclude_common=1) |
| Mullvad Base (Ads+Tracker+Malware) | base.dns.mullvad.net | [DNS-Over-HTTPS](https://github.com/mullvad/encrypted-dns-profiles/raw/refs/heads/main/base/mullvad-encrypted-dns-https-base.mobileconfig) [DNS-Over-TLS](https://github.com/mullvad/encrypted-dns-profiles/raw/refs/heads/main/base/mullvad-encrypted-dns-tls-base.mobileconfig)|
| AdGuard DNS | dns.adguard-dns.com | [DNS-Over-HTTPS](https://github.com/arfshl/personal-blocklist/raw/refs/heads/main/appledns/adguard-dns-doh.mobileconfig) [DNS-Over-TLS](https://github.com/arfshl/personal-blocklist/raw/refs/heads/main/appledns/adguard-dns-dot.mobileconfig) |

#### I also shared my personal configuration files, notes that this only optimized for my own devices, only use this for references
[AdGuard for Android](https://github.com/arfshl/personal-blocklist/archive/refs/heads/adguard-for-android-config.zip)

[Private AdGuard DNS](https://github.com/arfshl/personal-blocklist/raw/main/res/adguarddnsconfig.txt)

[uBlock Origin](https://github.com/arfshl/personal-blocklist/raw/main/res/ublock0config.txt)

[AdGuard Home for Windows](https://github.com/arfshl/personal-blocklist/raw/main/res/aghome-win.yaml)

[AdGuard Home for Linux](https://github.com/arfshl/personal-blocklist/raw/main/res/aghome-linux.yaml)
