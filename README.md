# DNS-Encryption
[DNS over TLS](https://en.wikipedia.org/wiki/DNS_over_TLS) &amp; [DNS over HTTPS](https://en.wikipedia.org/wiki/DNS_over_HTTPS) for iOS 14 and macOS Big Sur or newer systems.

## Details
- DNS over TLS(DoT) Port:853 
- DNS over HTTPS(DoH) Port:443

## Manual
Select a mobileconfig and raw to download a configuration profile.
On iOS, after installation, go to system Settings => General => Profile, select downloaded profile and click “Install” button.

## Cloudflare
- [DNS over TLS](https://github.com/MARCO-EMC/DNS-Encryption/raw/main/cloudflare-dot.mobileconfig)
- [DNS over HTTPS](https://github.com/MARCO-EMC/DNS-Encryption/raw/main/cloudflare-doh.mobileconfig)
- [Security](https://github.com/MARCO-EMC/DNS-Encryption/raw/main/cloudflare-security-doh.mobileconfig)
- [Family](https://github.com/MARCO-EMC/DNS-Encryption/raw/main/cloudflare-family-doh.mobileconfig)

## ADGuard


## Test URL
- [Cloudflare](https://1.1.1.1/help)
- [ADGuard](https://adguard.com/en/test.html)

## DNS over TLS vs. DNS over HTTPS | Secure DNS
DNS queries are sent in plaintext, which means anyone can read them. DNS over HTTPS and DNS over TLS encrypt DNS queries and responses to keep user browsing secure and private. However, both approaches have their pros and cons.

## Why does DNS need additional layers of security?
DNS is the phonebook of the Internet; DNS resolvers translate human-readable domain names into machine-readable IP addresses. By default, DNS queries and responses are sent in plaintext (via UDP), which means they can be read by networks, ISPs, or anybody able to monitor transmissions. Even if a website uses HTTPS, the DNS query required to navigate to that website is exposed.

This lack of privacy has a huge impact on security and, in some cases, human rights; if DNS queries are not private, then it becomes easier for governments to censor the Internet and for attackers to stalk users' online behavior.

Think of a normal, unencrypted DNS query as being like a postcard sent through the mail: anyone handling the mail may happen to catch a glimpse of the text written on the back side, so it is not wise to mail a postcard that contains sensitive or private information.

DNS over TLS and DNS over HTTPS are two standards developed for encrypting plaintext DNS traffic in order to prevent malicious parties, advertisers, ISPs, and others from being able to interpret the data. Continuing the analogy, these standards aim to put an envelope around all postcards going through the mail, so that anyone can send a postcard without worrying that someone is snooping on what they are up to.

## What is DNS over TLS?
DNS over TLS, or DoT, is a standard for encrypting DNS queries to keep them secure and private. DoT uses the same security protocol, TLS, that HTTPS websites use to encrypt and authenticate communications. (TLS is also known as "SSL.") DoT adds TLS encryption on top of the user datagram protocol (UDP), which is used for DNS queries. Additionally, it ensures that DNS requests and responses are not tampered with or forged via on-path attacks.
