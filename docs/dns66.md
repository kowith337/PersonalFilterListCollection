# DNS list table to apply in DNS66

| Provider | Features | Logging | First IP | Second IP | Compatibility |
|----------|----------|---------|----------|-----------|---------------|
| [CloudFlare + APNIC](https://1.1.1.1/) | [:lock_with_ink_pen:](https://cloudflare-dns.com/dns-query) | [:bust_in_silhouette: :watch:](https://developers.cloudflare.com/1.1.1.1/commitment-to-privacy/privacy-policy/privacy-policy) | 1.0.0.1 | 1.1.1.1 |  |
| [Comodo Secure](https://www.comodo.com/secure-dns) | :twisted_rightwards_arrows: |  | 8.20.247.20 | 8.26.56.26 |  |
| [Quad9](https://quad9.net) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) :closed_lock_with_key: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | 9.9.9.9 | 149.112.112.9 |  |
| [Quad9^2](https://quad9.net/doh-quad9-dns-servers) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) :closed_lock_with_key: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | 9.9.9.9 | 149.112.112.112 |  |
| [Quad9 HTTP](https://quad9.net/doh-quad9-dns-servers) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) | [:bust_in_silhouette:](https://quad9.net/privacy) | 9.9.9.10 | 149.112.112.110 |  |
| [Yandex](https://dns.yandex.com) |  |  | 77.88.8.1 | 77.88.8.8 |  |
| [Yandex Safe](https://dns.yandex.com) | :fire: |  | 77.88.8.2 | 77.88.8.88 |  |
| [Yandex Family](https://dns.yandex.com) | :fire: :children_crossing: |  | 77.88.8.3 | 77.88.8.7 |  |
| [dns.watch](https://dns.watch) | :closed_lock_with_key: | :negative_squared_cross_mark: | 84.200.69.80 | 84.200.70.40 |  |
| [Digital Courage](https://digitalcourage.de/support/zensurfreier-dns-server) |  |  | 85.214.20.141 |  |  |
| [eieiDNS](https://eieidns.com) | [:lock_with_ink_pen:](https://doh.eieidns.com/dns-query) :closed_lock_with_key: :no_pedestrians: |  | 103.86.49.31 |  |  |
| [AdGuard](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :no_pedestrians: |  | 176.103.130.130 | 176.103.130.131 |  |
| [AdGuard Family](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :no_pedestrians: :children_crossing: |  | 176.103.130.132 | 176.103.130.134 |  |
| [CleanBrowsing Security](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/security-filter) :closed_lock_with_key: :fire: |  | 185.228.168.9 | 185.228.169.9 |  |
| [CleanBrowsing Adult](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/adult-filter) :closed_lock_with_key: :children_crossing: :fire: |  | 185.228.168.10 | 185.228.169.10 |  |
| [CleanBrowsing Family](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/family-filter) :closed_lock_with_key: :children_crossing: :fire: |  | 185.228.168.168 | 185.228.169.168 |  |
| [AS250](https://twitter.com/as250) |  |  | 194.150.168.168 |  |  |
| [OpenDNS Family](https://www.opendns.com/setupguide/#familyshield) | :closed_lock_with_key: :twisted_rightwards_arrows: :children_crossing: |  | 208.67.220.123 | 208.67.222.123 |  |
| [OpenDNS](https://www.opendns.com) | :closed_lock_with_key: :twisted_rightwards_arrows: |  | 208.67.220.220 | 208.67.222.222 |  |
| [Chaos Computer Club](https://www.ccc.de/censorship/dns-howto) |  |  | 213.73.89.122 |  |  |
| [Oracle DynDNS](https://dyn.com/labs/dyn-internet-guide) |  | [:question:](https://dyn.com/legal/dyn-privacy-policy) | 216.146.35.35 | 216.146.36.36 |  |
| [dns.watch IPv6](https://dns.watch) | :closed_lock_with_key: :six: | :negative_squared_cross_mark: | 2001:1608:10:25::1c04:b12f | 2001:1608:10:25::9249:d69b |  |
| [CloudFlare + APNIC IPv6](https://1.1.1.1/) | [:lock_with_ink_pen:](https://cloudflare-dns.com/dns-query) :six: | [:bust_in_silhouette: :watch:](https://developers.cloudflare.com/1.1.1.1/commitment-to-privacy/privacy-policy/privacy-policy) | 2606:4700:4700::1001 | 2606:4700:4700::1111 |  |
| [OpenDNS IPv6](https://www.opendns.com/about/innovations/ipv6/) | :closed_lock_with_key: :six: :twisted_rightwards_arrows: |  | 2620:0:ccc::2 | 2620:0:ccd::2 |  |
| [Quad9 IPv6](https://quad9.net) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) :closed_lock_with_key: :six: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | 2620:fe::9 | 2620:fe::fe:9 |  |
| [Quad9^2 IPv6](https://quad9.net/doh-quad9-dns-servers) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) :closed_lock_with_key: :six: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | 2620:fe::fe | 2620:fe::fe:9 |  |
| [Quad9 HTTP IPv6](https://quad9.net/doh-quad9-dns-servers) | [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) :six: | [:bust_in_silhouette:](https://quad9.net/privacy) | 2620:fe::10 | 2620:fe::fe:10 |  |
| [AdGuard IPv6](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :six: :no_pedestrians: |  | 2a00:5a60::ad1:0ff | 2a00:5a60::ad2:0ff |  |
| [AdGuard Family IPv6](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :six: :no_pedestrians: :children_crossing: |  | 2a00:5a60::bad1:0ff | 2a00:5a60::bad2:0ff |  |
| [CleanBrowsing Family IPv6](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/family-filter) :closed_lock_with_key: :six: :children_crossing: :fire: |  |  | 2a0d:2a00:1:: | 2a0d:2a00:2:: |
| [CleanBrowsing Adult IPv6](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/adult-filter) :closed_lock_with_key: :six: :children_crossing: :fire: |  |  | 2a0d:2a00:1::1 | 2a0d:2a00:2::1 |  |
| [CleanBrowsing Security IPv6](https://cleanbrowsing.org/filters) | [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/security-filter) :closed_lock_with_key: :six: :fire: |  | 2a0d:2a00:1::2 | 2a0d:2a00:2::2 |  |
| [Digital Courage IPv6](https://digitalcourage.de/support/zensurfreier-dns-server) | :six: |  | 2a01:238:42f6:ac00:2a29:4f7f:b6d:ef46 |  |  |
| [Yandex IPv6](https://dns.yandex.com) | :six: |  | 2a02:6b8::feed:0ff | 2a02:6b8:0:1::feed:0ff |  |
| [Yandex Safe IPv6](https://dns.yandex.com) | :six: :fire: |  | 2a02:6b8::feed:bad | 2a02:6b8:0:1::feed:bad |  |
| [Yandex Family IPv6](https://dns.yandex.com) | :six: :fire: :children_crossing: |  | 2a02:6b8::feed:a11 | 2a02:6b8:0:1::feed:a11 |  |
| [OpenNIC](https://www.opennic.org) |  |  | [Tier 1](https://servers.opennic.org/?tier=1) | [Tier 2](https://servers.opennic.org/?tier=2) |  |
| **Retired** |  |  |  |  |  |
| [Norton ConnectSafe](https://dns.norton.com) | :fire: |  | 199.85.126.10 | 199.85.127.10 |  |
| [Norton + Adult](https://dns.norton.com) | :fire: :children_crossing: |  | 199.85.126.20 | 199.85.127.20 |  |
| [Norton + Adult + Other](https://dns.norton.com) | :fire: :children_crossing: |  | 199.85.126.30 | 199.85.127.30 |  |
|  |  |  |  |  |  |

- - - - - - - - - -

## Legends
#### Features
| Icon | Description |
|------|-------------|
| :lock_with_ink_pen: | DoH available (Right click to copy address) |
| :closed_lock_with_key: | DNSSEC available |
| :twisted_rightwards_arrows: | Multi-servers |
| :no_pedestrians: | Block ads and trackers |
| :children_crossing: | Family Protection (may include adult sites filtering) |
| :fire: | Thread blocking (Bots, Fraud, Malware, Spam) |

#### Logging
| Icon | Description |
|------|-------------|
|  | Unspecified |
| :negative_squared_cross_mark: | No Logging |
| :question: | Logging terms is unclear enough |
| :bust_in_silhouette: | Anonymous Log (e.g. Partial IP address) |
| :person_with_pouting_face: | Identifiable Log (e.g. Full IP address, devices, hardware, etc.) |
| :alarm_clock: | Logged permanently |
| :watch: | Logs will kept for specific time and will remove after |
| :open_file_folder: | May share logs to others (e.g. Partners, Threads watcher, etc.) |

Note: you can click to the emoji to view their terms (if available)

#### Compatible
| Icon | Description |
|------|-------------|
|  | Untested |
| :heavy_check_mark: | Compatible to block domains. |
| :interrobang: | Can block, but not all domains. |
| :x: | Fail to do it. |