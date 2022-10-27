# Awesome Go Project For Security Needs

_A curated list of various bug bounty tools_

## [OJ/GoBuster](https://github.com/OJ/gobuster) - Directory/File, DNS and VHost busting tool written in Go

Gobuster is a tool used to brute-force:

- URIs (directories and files) in web sites.
- DNS subdomains (with wildcard support).
- Virtual Host names on target web servers.

## [jaeles-project/GoSpider](https://github.com/jaeles-project/gospider) - Fast web spider written in Go

Features:

- Fast web crawling
- Brute force and parse sitemap.xml
- Parse robots.txt
- Generate and verify link from JavaScript files
- Link Finder
- Find AWS-S3 from response source
- Find subdomains from response source
- Get URLs from Wayback Machine, Common Crawl, Virus Total, Alien Vault
- Format output easy to Grep
- Support Burp input
- Crawl multiple sites in parallel
- Random mobile/web User-Agent

## [j3ssie/Osmedeus](https://github.com/j3ssie/osmedeus) - A Workflow Engine for Offensive Security

Key Features of Osmedeus

- Significantly speed up your recon process
- Organize your scan results
- Efficiently to customize and optimize your recon process
- Seamlessly integrate with new public and private tools
- Easy to scale across large number of targets
- Easy to synchronize the results across many places

## [kitabisa/teler](https://github.com/kitabisa/teler) - Real-time HTTP Intrusion Detection

Features

- Real-time: Analyze logs and identify suspicious activity in real-time.
- Alerting: teler provides alerting when a threat is detected, push notifications include Slack, Mattermost, Telegram and Discord.
- Monitoring: We've our own metrics if you want to monitor threats easily, and we use Prometheus for that.
- Logging: is also provided in file form or sends detected threats to the Zinc logs search engine.
- Latest resources: Collections is continuously up-to-date.
- Minimal configuration: You can just run it against your log file, write the log format and let teler analyze the log and show you alerts!
- Flexible log formats: teler allows any custom log format string! It all depends on how you write the log format in configuration file.
- Custom threat rules: Want to reach a wider range of threats instead of engine-based (default) rules? You can customize threat rules!
- Incremental log processing: Need data persistence rather than [buffer stream](https://linux.die.net/man/1/stdbuf)? teler has the ability to process logs incrementally through the on-disk persistence options.

## [pwnesia/dnstake](https://github.com/pwnesia/dnstake) — A fast tool to check missing hosted DNS zones that can lead to subdomain takeover

What is a DNS takeover?

DNS takeover vulnerabilities occur when a subdomain (subdomain.example.com) or domain has its authoritative nameserver set to a provider (e.g. AWS Route 53, Akamai, Microsoft Azure, etc.) but the hosted zone has been removed or deleted. Consequently, when making a [request for DNS records](https://www.diggui.com/#type=A&hostname=github.technology&nameserver=public&public=8.8.8.8&specify=&clientsubnet=&tcp=def&transport=def&mapped=def&nssearch=def&trace=def&recurse=def&edns=def&dnssec=def&subnet=def&cookie=def&all=def&cmd=def&question=def&answer=def&authority=def&additional=def&comments=def&stats=def&multiline=def&short=def&colorize=on) the server responds with a SERVFAIL error. This allows an attacker to create the missing hosted zone on the service that was being used and thus control all DNS records for that (sub)domain.

## [Nhoya/gOSINT](https://github.com/Nhoya/gOSINT) - OSINT Swiss Army Knife

What gOSINT can do? Currently gOSINT has different modules:

- git support for mail retriving (using github API, or plain clone and search)
- Search for mails, aliases and KeyID in PGP Server
- haveibeenpwned.com/ search for mail in databreach
- Retrieve Telegram Public Group Message History
- Search for mail address in source
- shodan.io search
- Subdomain enumeration using crt.sh
- Given a phone number, can retrieve the owner name
- Search for password relatives to email address :P
- Reverse Whois given Email Address or Name

## [projectdiscovery/naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with a focus on reliability and simplicity

Features :

- Fast And Simple SYN/CONNECT probe based scanning
- Optimized for ease of use and lightweight on resources
- DNS Port scan
- Automatic IP Deduplication for DNS port scan
- IPv4/IPv6 Port scan (experimental)
- Passive Port enumeration using Shodan Internetdb
- Host Discovery scan (experimental)
- NMAP integration for service discovery
- Multiple input support - STDIN/HOST/IP/CIDR/ASN
- Multiple output format support - JSON/TXT/STDOUT

## [projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder) - Subfinder is a subdomain discovery tool that discovers valid subdomains for websites

Features :

- Fast and powerful resolution and wildcard elimination module
- Curated passive sources to maximize results
- Multiple Output formats supported (Json, File, Stdout)
- Optimized for speed, very fast and lightweight on resources
- STDIN/OUT support for integrating in workflows

## [projectdiscovery/nuclei](https://github.com/projectdiscovery/nuclei) - Fast and customizable vulnerability scanner based on simple YAML based DSL

For Security Engineers :

Nuclei offers great number of features that are helpful for security engineers to customise workflow in their organisation. With the varieties of scan capabilities (like DNS, HTTP, TCP), security engineers can easily create their suite of custom checks with Nuclei.

- Varieties of protocols supported: TCP, DNS, HTTP, File, etc
- Achieve complex vulnerability steps with workflows and dynamic requests.
- Easy to integrate into CI/CD, designed to be easily integrated into regression cycle to actively check the fix and re-appearance of vulnerability.

## [projectdiscovery/httpx](https://github.com/projectdiscovery/httpx) - httpx is a fast and multi-purpose HTTP toolkit.

Features :

- Simple and modular code base making it easy to contribute.
- Fast And fully configurable flags to probe multiple elements.
- Supports multiple HTTP based probings.
- Smart auto fallback from https to http as default.
- Supports hosts, URLs and CIDR as input.
- Handles edge cases doing retries, backoffs etc for handling WAFs.

## [ffuf/ffuf](https://github.com/ffuf/ffuf) - Fast web fuzzer written in Go

## [dwisiswant0/crlfuzz](https://github.com/dwisiswant0/crlfuzz) - A fast tool to scan CRLF vulnerability written in Go

<!-- gobuster, ffuf, jaeles, gospide,  -->
