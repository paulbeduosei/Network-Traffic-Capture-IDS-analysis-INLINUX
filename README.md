# Network-Traffic-Capture-IDS-analysis-INLINUX

I used Suricata to run IDS/alerting on a packet capture, reviewed generated logs and alerts, and parsed the JSON output to extract key fields. 

The work included creating a custom rule, running Suricata against a pcap, reviewing the produced logs in /var/log/suricata, and attempting to filter records with jq.

I created and tested a custom Suricata rule, ran the IDS engine against packet captures, inspected the generated alert logs (fast.log and eve.json), and parsed findings with ‘jq’ to extract relevant fields.

This workflow illustrates end-to-end detection and analysis: rule authoring → packet scanning → alert logging → structuredJSON parsing for downstream analysis or reporting.
