# [DNS-Encryption](https://blog.cloudflare.com/dns-encryption-explained/)
[DNS over TLS](https://en.wikipedia.org/wiki/DNS_over_TLS) &amp; [DNS over HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) for [iOS 14](https://www.apple.com/ios/ios-14/) and [macOS Big Sur](https://www.apple.com/macos/big-sur/) or newer systems.

------------------------------------------------------

## Shortcuts

## [ADGuard](https://adguard.com/en/adguard-dns/overview.html)
- [DNS over TLS](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-doh.mobileconfig)
- [DNS over TLS Family protection](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-family-dot.mobileconfig)
- [DNS over HTTPS Family protection](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-family-doh.mobileconfig)
- [DNS over TLS Non-filtering](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-unfiltered-dot.mobileconfig)
- [DNS over HTTPS Non-filtering](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-unfiltered-doh.mobileconfig)
- [Verified ADGuard DNS](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-dns.mobileconfig)
- [Verified AdGuard DNS Family protection](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-dns-family.mobileconfig)
- [Verified AdGuard DNS Non-filtering](https://github.com/maaarcooo/DNS-Encryption/raw/main/adguard-dns-unfiltered.mobileconfig)

## [Cloudflare](https://1.1.1.1/)
- [DNS over TLS](https://github.com/maaarcooo/DNS-Encryption/raw/main/cloudflare-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/cloudflare-doh.mobileconfig)
- [DNS over HTTPS Security](https://github.com/maaarcooo/DNS-Encryption/raw/main/cloudflare-security-doh.mobileconfig)
- [DNS over HTTPS Family](https://github.com/maaarcooo/DNS-Encryption/raw/main/cloudflare-family-doh.mobileconfig)

## [Google](https://developers.google.com/speed/public-dns/)
- [DNS over TLS](https://github.com/maaarcooo/DNS-Encryption/raw/main/google-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/google-doh.mobileconfig)

## [NextDNS](https://nextdns.io/)
- [DNS over TLS](https://github.com/maaarcooo/DNS-Encryption/raw/main/nextdns-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/nextdns-doh.mobileconfig)
- [Verified NextDNS](https://github.com/maaarcooo/DNS-Encryption/raw/main/nextdns-1b5712.mobileconfig)

## [OpenDNS](https://support.opendns.com/hc/en-us/articles/360038086532-Using-DNS-over-HTTPS-DoH-with-OpenDNS)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/opendns-doh.mobileconfig)
- [DNS over HTTPS FamilyShield](https://github.com/maaarcooo/DNS-Encryption/raw/main/opendns-familyshield-doh.mobileconfig)

## [Quad9](https://quad9.net/service/service-addresses-and-features)
- [DNS over TLS](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-doh.mobileconfig)
- [DNS over TLS ECS](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-ecs-dot.mobileconfig)
- [DNS over HTTPS ECS](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-ecs-doh.mobileconfig)
- [DNS over TLS Unsecured](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-unsecured-dot.mobileconfig)
- [DNS over HTTPS Unsecured](https://github.com/maaarcooo/DNS-Encryption/raw/main/quad9-unsecured-doh.mobileconfig)

------------------------------------------------------

## Features
| [DNSSec](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) | No Logs | [IPv4](https://en.wikipedia.org/wiki/IPv4) | [IPv6](https://en.wikipedia.org/wiki/IPv6) | No Filter | Family Filter | [Ad blocking](https://en.wikipedia.org/wiki/Ad_blocking) | Malware filter |

- [Cloudflare](https://1.1.1.1/) DNSSec | No Logs | No Filter | IPv4 | IPv6
- [Security](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families/setup-instructions/dns-over-https) DNSSec | No Logs | IPv4 | IPv6 | Malware filter
- [Family](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families/setup-instructions/dns-over-https) DNSSec | No Logs | IPv4 | IPv6 | Family Filter | Malware filter
- [ADGuard](https://adguard.com/en/adguard-dns/overview.html) DNSSec | No Logs | IPv4 | IPv6 | Ad blocking
- [Family protection](https://adguard.com/en/adguard-dns/overview.html) DNSSec | No Logs | IPv4 | IPv6 | Family Filter | Ad blocking
- [Non-filtering](https://adguard.com/en/adguard-dns/overview.html) DNSSec | No Logs | IPv4 | IPv6 | No Filter
- [Google](https://developers.google.com/speed/public-dns/) DNSSec | IPv4 | IPv6 | No Filter
- [Quad9](https://quad9.net/service/service-addresses-and-features) DNSSec | No Logs | IPv4 | IPv6 | Malware filter
- [ECS](https://quad9.net/service/service-addresses-and-features#ecssec) DNSSec | No Logs | IPv4 | IPv6 | Malware filter
- [Unsecured](https://quad9.net/service/service-addresses-and-features#unsec) DNSSec | No Logs | IPv4 | IPv6 | No Filter
- [OpenDNS](https://www.opendns.com/home-internet-security/) DNSSec | IPv4 | IPv6
- [FamilyShield](https://www.opendns.com/setupguide/#familyshield) DNSSec | IPv4 | IPv6 | Family Filter
- [NextDNS](https://nextdns.io/) DNSSec | No Logs | IPv4 | IPv6 | Family Filter | Ad blocking | Malware filter (Custom)

## Compare
- Cloudflare is the fastest DNS.
- ADGuard  #Adblock
- Quad9  #Malware filter
- NextDNS  #Custom setting
## Manual
Select a mobileconfig and raw to download a configuration profile.
On iOS, after installation, go to system Settings => General => Profile, select downloaded profile and click “Install” button.

## Test URL
- [Cloudflare](https://1.1.1.1/help)
- [ADGuard](https://adguard.com/en/test.html)
- [DNS leak test](https://surfshark.com/dns-leak-test) by [Surfshark](https://surfshark.com/)

------------------------------------------------------

## [DNS over TLS vs. DNS over HTTPS | Secure DNS](https://www.cloudflare.com/learning/dns/dns-over-tls/)
DNS queries are sent in plaintext, which means anyone can read them. DNS over HTTPS and DNS over TLS encrypt DNS queries and responses to keep user browsing secure and private. However, both approaches have their pros and cons.

## Why does DNS need additional layers of security?
[DNS](https://www.cloudflare.com/learning/dns/what-is-dns/) is the phonebook of the Internet; DNS resolvers translate human-readable domain names into machine-readable [IP addresses](https://www.cloudflare.com/learning/dns/glossary/what-is-my-ip-address/). By default, DNS queries and responses are sent in plaintext (via [UDP](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/)), which means they can be read by networks, ISPs, or anybody able to monitor transmissions. Even if a website uses [HTTPS](https://www.cloudflare.com/learning/ssl/what-is-https/), the DNS query required to navigate to that website is exposed.

This lack of privacy has a huge impact on security and, in some cases, human rights; if DNS queries are not private, then it becomes easier for governments to censor the Internet and for attackers to stalk users' online behavior.

![images](https://images.ctfassets.net/slt3lc6tev37/5Cgzkxb8COyIZ9evqqGFyF/384df7ee28643474080bbcd564fc3cfa/dns-traffic-unsecured.svg)

Think of a normal, unencrypted DNS query as being like a postcard sent through the mail: anyone handling the mail may happen to catch a glimpse of the text written on the back side, so it is not wise to mail a postcard that contains sensitive or private information.

DNS over [TLS](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/) and DNS over [HTTPS](https://www.cloudflare.com/learning/ssl/what-is-https/) are two standards developed for encrypting plaintext DNS traffic in order to prevent malicious parties, advertisers, ISPs, and others from being able to interpret the data. Continuing the analogy, these standards aim to put an envelope around all postcards going through the mail, so that anyone can send a postcard without worrying that someone is snooping on what they are up to.

![images](https://images.ctfassets.net/slt3lc6tev37/7qcyOJwWyOt4EVJykiIRTn/30e34453409eb42fa1ec36680609ad8d/dns-traffic-over-tls-https.svg)

## What is DNS over TLS?
DNS over TLS, or DoT, is a standard for encrypting DNS queries to keep them secure and private. DoT uses the same security protocol, TLS, that HTTPS websites use to encrypt and authenticate communications. (TLS is also known as "[SSL](https://www.cloudflare.com/learning/ssl/what-is-ssl/).") DoT adds TLS encryption on top of the user datagram protocol (UDP), which is used for DNS queries. Additionally, it ensures that DNS requests and responses are not tampered with or forged via [on-path attacks](https://www.cloudflare.com/learning/security/threats/on-path-attack/).

## What is DNS over HTTPS?
DNS over HTTPS, or DoH, is an alternative to DoT. With DoH, DNS queries and responses are encrypted, but they are sent via the HTTP or HTTP/2 protocols instead of directly over UDP. Like DoT, DoH ensures that attackers can't forge or alter DNS traffic. DoH traffic looks like other HTTPS traffic – e.g. normal user-driven interactions with websites and web apps – from a network administrator's perspective.

In February 2020, the Mozilla Firefox browser began enabling DoH for U.S. users by default. DNS queries from the Firefox browser are encrypted by DoH and go to either Cloudflare or NextDNS. Several other browsers also support DoH, although it is not turned on by default.

## Wait, doesn't HTTPS use TLS for encryption too? How are DNS over TLS and DNS over HTTPS different?
Each standard was developed separately and has its own RFC* documentation, but the most important difference between DoT and DoH is what port they use. DoT only uses port 853, while DoH uses port 443, which is the port that all other HTTPS traffic uses as well.

Because DoT has a dedicated port, anyone with network visibility can see DoT traffic coming and going, even though the requests and responses themselves are encrypted. In contrast, with DoH, DNS queries and responses are camouflaged within other HTTPS traffic, since it all comes and goes from the same port.

*RFC stands for "Request for Comments", and an RFC is a collective attempt by developers, networking experts, and thought leaders to standardize an Internet technology or protocol.

## What is a port?
In networking, a port is a virtual place on a machine that is open to connections from other machines. Every networked computer has a standard number of ports, and each port is reserved for certain types of communication.

Think of ports for ships in a harbor: each shipping port is numbered, and different kinds of ships are supposed to go to specific shipping ports to unload cargo or passengers. Networking is the same way: certain types of communications are supposed to go to certain network ports. The difference is that the network ports are virtual; they are places for digital connections rather than physical connections.

## Which is better, DoT or DoH?
This is up for debate. From a network security standpoint, DoT is arguably better. It gives network administrators the ability to monitor and block DNS queries, which is important for identifying and stopping malicious traffic. DoH queries, meanwhile, are hidden in regular HTTPS traffic, meaning they cannot easily be blocked without blocking all other HTTPS traffic as well.

However, from a privacy perspective, DoH is arguably preferable. With DoH, DNS queries are hidden within the larger flow of HTTPS traffic. This gives network administrators less visibility but provides users with more privacy.

[1.1.1.1, the free DNS resolver from Cloudflare](https://1.1.1.1/), supports both DoT and DoH.

## What is the difference between DNS over TLS/HTTPS and DNSSEC?
[DNSSEC](https://www.cloudflare.com/learning/dns/dns-security/) is a set of security extensions for verifying the identity of [DNS root servers](https://www.cloudflare.com/learning/dns/glossary/dns-root-server/) and authoritative nameservers in communications with [DNS resolvers](https://www.cloudflare.com/learning/dns/dns-server-types/). It is designed to prevent [DNS cache poisoning](https://www.cloudflare.com/learning/dns/dns-cache-poisoning/), among other attacks. It does not encrypt communications. DNS over TLS or HTTPS, on the other hand, does encrypt DNS queries. 1.1.1.1 supports DNSSEC as well.

To learn more about 1.1.1.1, see [What is 1.1.1.1?](https://www.cloudflare.com/learning/dns/what-is-1.1.1.1/)

By [Cloudflare](https://www.cloudflare.com/learning/dns/dns-over-tls/)

[DNSSettings](https://developer.apple.com/documentation/devicemanagement/dnssettings)

[Developer](https://developer.apple.com/)
