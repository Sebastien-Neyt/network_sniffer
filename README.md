# network_sniffer
-   The arp_poison.py script will convince the targets system that we have become its default gateway.
It will then sniff x amount of packages and store them in a pcap file for you to analyze.
Running the script looks like this:
`sudo python3 arp_poison.py [target IP] [gateway IP] [interface]`


-   In pcap_extractor/recapper.py, I'm trying to parse the pcap file and extract all packets with a source/destination port of 80.
After that it tries to extract all images from the recorded traffic.

