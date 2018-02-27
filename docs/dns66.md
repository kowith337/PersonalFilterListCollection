# DNS list table to apply in DNS66

| Provider | Features | Logging | First IP | Second IP | Compatibility |
|----------|----------|---------|----------|-----------|---------------|
| [Comodo Secure](https://www.comodo.com/secure-dns) | :twisted_rightwards_arrows: | :grey_question: | 8.20.247.20 | 8.26.56.26 | :grey_question: |
| [Quad9](https://www.quad9.net) | :fire: | [:question:](https://www.quad9.net/faq) :computer: |  |  |  |
| [Yandex](https://dns.yandex.com) |  | :grey_question: | 77.88.8.1 | 77.88.8.8 | :grey_question: |
| [Yandex Safe](https://dns.yandex.com) | :fire: | :grey_question: | 77.88.8.2 | 77.88.8.88 | :grey_question: |
| [Yandex Family](https://dns.yandex.com) | :fire: :children_crossing: | :grey_question: | 77.88.8.3 | 77.88.8.7 | :grey_question: |
| [dns.watch](https://dns.watch) | :closed_lock_with_key: | :negative_squared_cross_mark: | 84.200.69.80 | 84.200.70.40 | :grey_question: |
| [AdGuard](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: | :grey_question: | 176.103.130.130 | 176.103.130.131 | :grey_question: |
| [AdGuard Family](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :children_crossing: | :grey_question: | 176.103.130.132 | 176.103.130.134 | :grey_question: |
| [Norton ConnectSafe](https://dns.norton.com) | :fire: | :grey_question: | 199.85.126.10 | 199.85.127.10 | :grey_question: |
| [Norton + Adult](https://dns.norton.com) | :fire: :children_crossing: | :grey_question: | 199.85.126.20 | 199.85.127.20 | :grey_question: |
| [Norton + Adult + Other](https://dns.norton.com) | :fire: :children_crossing: | :grey_question: | 199.85.126.30 | 199.85.127.30 | :grey_question: |
| [OpenDNS Family](https://www.opendns.com/setupguide/#familyshield) | :closed_lock_with_key: :twisted_rightwards_arrows: :children_crossing: | :grey_question: | 208.67.220.123 | 208.67.222.123 | :grey_question: |
| [OpenDNS](https://www.opendns.com) | :closed_lock_with_key: :twisted_rightwards_arrows: | :grey_question: | 208.67.220.220 | 208.67.222.222 | :grey_question: |
| [Oracle DynDNS](https://dyn.com/labs/dyn-internet-guide) |  | [:question:](https://dyn.com/legal/dyn-privacy-policy) | 216.146.35.35 | 216.146.36.36 | :grey_question: |
| [dns.watch IPv6](https://dns.watch) | :closed_lock_with_key: :six: | :negative_squared_cross_mark: | 2001:1608:10:25::1c04:b12f | 2001:1608:10:25::9249:d69b | :grey_question: |
| [OpenDNS IPv6](https://www.opendns.com/about/innovations/ipv6/) | :closed_lock_with_key: :six: :twisted_rightwards_arrows: | :grey_question: | 2620:0:ccc::2 | 2620:0:ccd::2 | :grey_question: |
| [AdGuard IPv6](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :six: | :grey_question: | 2a00:5a60::ad1:0ff | 2a00:5a60::ad2:0ff | :grey_question: |
| [AdGuard Family IPv6](https://adguard.com/en/adguard-dns/overview.html) | :closed_lock_with_key: :six: :children_crossing: | :grey_question: | 2a00:5a60::bad1:0ff | 2a00:5a60::bad2:0ff | :grey_question: |
| [Yandex IPv6](https://dns.yandex.com) | :six: | :grey_question: | 2a02:6b8::feed:0ff | 2a02:6b8:0:1::feed:0ff | :grey_question: |
| [Yandex Safe IPv6](https://dns.yandex.com) | :six: :fire: | :grey_question: | 2a02:6b8::feed:bad | 2a02:6b8:0:1::feed:bad | :grey_question: |
| [Yandex Family IPv6](https://dns.yandex.com) | :six: :fire: :children_crossing: | :grey_question: | 2a02:6b8::feed:a11 | 2a02:6b8:0:1::feed:a11 | :grey_question: |
| [OpenNIC](https://www.opennic.org) | :grey_question: | :grey_question: | [Tier 1](https://servers.opennic.org/?tier=1) | [Tier 2](https://servers.opennic.org/?tier=2) | :grey_question: |
|  |  |  |  |  |  |

- - - - - - - - - -

## Legends
#### Features
| Icon | Description |
|------|-------------|
| :closed_lock_with_key: | DNSSEC available |
| :twisted_rightwards_arrows: | Multi-servers |
| :children_crossing: | Family Protection (may include adult sites filtering) |
| :fire: | Thread blocking (Bots, Fraud, Malware, Spam) |

#### Logging
| Icon | Description |
|------|-------------|
| :grey_question: | Unspecified |
| :negative_squared_cross_mark: | No Logging |
| :question: | Logged with specific interval or by terms |
| :heavy_exclamation_mark: | Logged permanently |

Note: you can click to the logging emoji to view the terms (if available)

#### Compatible
| Icon | Description |
|------|-------------|
| :grey_question: | Untested |
| :heavy_check_mark: | Compatible to block domains. |
| :interrobang: | Can block, but not all domains. |
| :x: | Fail to do it. |