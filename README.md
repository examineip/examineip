### Hi, this is ExamineIP 👋

Free IP, DNS and network tools, with plain-English guides that explain what the results mean.
No signup, no ads, and lookups aren't stored.

**🔍 IP & privacy**
[What Is My IP](https://tools.examineip.com/) ·
[VPN Leak Test](https://tools.examineip.com/vpn-leak-test/) ·
[IP Reputation](https://tools.examineip.com/ip-reputation/) ·
[Bulk IP Lookup](https://tools.examineip.com/bulk-ip-lookup/) ·
[Port Scanner](https://tools.examineip.com/port-scanner/) ·
[IPv6 Readiness Test](https://tools.examineip.com/ipv6-test/) ·
[Privacy Exposure Score](https://examineip.com/privacy-exposure-score/)

**🌐 DNS**
[DNS Checker](https://tools.examineip.com/dns-checker/) ·
[DNS Propagation Checker](https://tools.examineip.com/dns-propagation-checker/) ·
[DNSSEC Checker](https://tools.examineip.com/dnssec-checker/) ·
[WHOIS Lookup](https://tools.examineip.com/whois-lookup/)

**📡 Network diagnostics**
[Ping Test](https://tools.examineip.com/ping-test/) ·
[Speed Test](https://tools.examineip.com/speed-test/) ·
[Subnet Calculator](https://tools.examineip.com/subnet-calculator/)

**✉️ Email authentication**
[DMARC / SPF / DKIM Checker](https://tools.examineip.com/dmarc-checker/) ·
[Email Header Analyzer](https://tools.examineip.com/email-header-analyzer/) ·
[DMARC Report Reader](https://tools.examineip.com/dmarc-report-reader/)

**🔐 Web security**
[SSL Certificate Checker](https://tools.examineip.com/ssl-checker/) ·
[HTTP Security Headers](https://tools.examineip.com/security-headers/) ·
[Lookalike Domain Checker](https://tools.examineip.com/homograph-checker/) ·
[QR Code Decoder](https://tools.examineip.com/qr-decoder/)

**🛠️ Utilities**
[Encoding & hashing](https://tools.examineip.com/encoding-tools/) ·
[Password tools](https://tools.examineip.com/password-tools/)

**📚 Learn**
[Guides](https://examineip.com/) ·
[Scam Test](https://examineip.com/scam-test/) ·
[Data-broker opt-out directory](https://examineip.com/delete-yourself/) ·
[Books](https://examineip.com/books/)

---

**How the tools are built**

- Every result comes from a real query or measurement — nothing is guessed or padded.
- Each tool says what it *can't* tell you, not just what it can.
- Where a check needs a server (IP lookup, blacklist check, port scan), the result is returned and not kept.

**Open source here**

- [**dnsbl-check**](https://github.com/examineip/dnsbl-check) — a DNS blacklist checker that doesn't
  report refused queries as listings, timeouts as clean, or dead lists at all.
- [**doh-compare**](https://github.com/examineip/doh-compare) — asks Google and Cloudflare the same DNS
  question over DoH and tells real differences from quoting, ordering and GeoDNS noise.
- [**webrtc-leak-check**](https://github.com/examineip/webrtc-leak-check) — WebRTC IP leak detection
  without the false alarms: ignores mDNS and private addresses, compares per IP family.
  [Live demo](https://examineip.github.io/webrtc-leak-check/demo.html)
- [**rdap-lookup**](https://github.com/examineip/rdap-lookup) — readable WHOIS for domains and IPs over
  RDAP; tells "not registered" apart from "this TLD has no RDAP".
- [**email-auth-headers**](https://github.com/examineip/email-auth-headers) — explains SPF, DKIM and DMARC
  from raw email headers without flagging legitimate newsletters as suspicious.
- [**password-tools**](https://github.com/examineip/password-tools) — honest strength estimates,
  crypto-random generators with the EFF wordlist, and a private Have I Been Pwned check.
- [**subnet-calc**](https://github.com/examineip/subnet-calc) — IPv4 subnet arithmetic with `/0`, `/31`,
  `/32` and mask edge cases done properly, tested against Python's `ipaddress`.

Every repo has an offline test suite running in CI, and each tool is live, free and signup-free
on the site.

📫 contact@examineip.com
