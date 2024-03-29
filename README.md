# MSCTUD DNS-over-TLS Dataset

Dataset part of research project to detect DNS tunnelling over a DoT encrypted link using Machine Learning.

![Network Topology](https://github.com/heff09/MSCTUD_DNS-over-TLS/assets/41806354/878bb0fc-f3d6-4b4a-bd3f-6dc2aef7052e)

Iodine, DNSteal and PowerDNS DNS tunnelling tools were used to establish connections to a malicious server hosted in 
the cloud. The malicious server facilitated Proxy Web traffic, Data exfiltration and Data Infiltration tunnels through a DNS-over-TLS encrypted channel to Google Public DNS resolver.

Flows extracted using Tranalyzer2 and CICFlowmeter feature extraction tools from multiple network captures defined by the scenarios being investigated.

Dataset comprises:
==================
Tranalyzer2 extracted flows and statistical information, raw features saved to each csv file.

CICFlowmeter extracted flows and statistical information, raw features saved to each csv file.

Original PCAP files with TCP port 853 TLS traffic
