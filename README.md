# ddos-protection
a collection of links about DDoS Protection

## I want to help

Do you have tips or packet captures (pcap, pcapng, sflow) that you are willing to share? Please open up a github issue / PR and share them.

## Interesting opensource projects
https://github.com/pavel-odintsov/fastnetmon ddos detection from sFlow.

https://github.com/jjsantanna/pcap_dns_ddos_analysis packet capture analysis for automation and better understanding a attack


XDP is also a very promising technology for ddos protection:

https://www.mcorbin.fr/pages/xdp-introduction/ introduction article to XDP

https://github.com/xdp-project/xdp-tutorial The holy grail of XDP information. This repository contains a lot of getting-started information for packet handling in the kernel.

https://github.com/PlushBeaver/xdp-syn-cookie syn cookies implemented in XDP space. About 50% faster when runnning in SKB mode than the normal kernel system and toggleable on demand.

https://github.com/matthewbentley/ebpf-flowradar WIP flowradar implementation in XDP using bloom filters


More research:
https://github.com/Phenomite/AMP-Research UDP amplification ports

https://gitlab.com/cryptio/ddos-research/-/tree/master chase's anti ddos research.



Good DDoS-related reads:
https://blog.cloudflare.com/meet-gatebot-a-bot-that-allows-us-to-sleep/

https://blog.cloudflare.com/l4drop-xdp-ebpf-based-ddos-mitigations/

https://blog.cloudflare.com/how-to-drop-10-million-packets/

https://ebpf.io/

https://developers.redhat.com/blog/2018/12/06/achieving-high-performance-low-latency-networking-with-xdp-part-1/

Others that might be worth a look

https://jvns.ca/blog/2017/04/07/xdp-bpf-tutorial/

https://essay.utwente.nl/80125/1/vanwieren_MA_DACS.pdf

https://events19.linuxfoundation.org/wp-content/uploads/2017/12/Super-Fast-Packet-Filtering-with-eBPF-and-XDP-Helen-Tabunshchyk-Cloudflare-1.pdf





### Other
// TODO, want to contribute? Please open up a PR or github issue.
