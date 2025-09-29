Wireshark Protocol Analysis

📁 Task Overview
This task documents the process of capturing and analyzing network traffic using Wireshark on a Kali Linux VM. The goal was to identify key protocols, inspect packet details, and summarize findings for professional reporting.

🔄 Traffic Generation
- Firefox browser was used inside the Kali VM.
- Visited: [https://www.kernel.org](https://www.kernel.org)
- This generated DNS queries, TCP connections, and encrypted TLS traffic.

📦 Packet Capture Details
- Capture file: `wireshark_capture_day5_task5.pcap`
- Total packets captured: 622
- Protocols observed: DNS, TCP, TLS

🔍 Protocol Summaries

| Protocol | Filter Used | Screenshot | Notes File |
|----------|-------------|------------|------------|
| DNS      | `dns`       | `dns_filter_view.png` | `dns_filter.txt` |
| TCP      | `tcp`       | `tcp_filter_view.png` | `tcp_filter.txt` |
| TLS      | `tls`       | `tls_filter_view.png` | `tls_filter.txt` |

> Note: HTTP was not observed during this session. All IP addresses have been redacted for privacy.


📑 Documentation Files
- `generate_traffic.txt`: Describes how traffic was generated
- `summary_of_findings.txt`: Summarizes protocol behavior and packet insights
- Individual `.txt` files for each protocol with packet-level observations

🔒 Privacy & Compliance
- All IP addresses have been redacted from documentation.
- Screenshots show full packet views without display filters.
- No sensitive data was captured or stored.

✅ Outcome
This task confirms successful traffic generation, packet capture, and protocol analysis using Wireshark. Screenshots and summaries provide a reproducible audit trail suitable for internship reporting and portfolio documentation.
