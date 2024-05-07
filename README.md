# PacketSniffer

This is a Python project for a basic packet sniffer. A packet sniffer is a tool used to capture and analyze network traffic. It intercepts and logs traffic passing over a network, allowing users to inspect the data being transmitted between devices.

### Requirements

Ensure you have Python and scapy installed on your system.
Run the packet_sniffer.py script.
Optionally, specify the network interface you want to sniff packets on (eth0, wlan0, etc.).
Optionally, apply filters to capture specific types of traffic.
View the captured packet information in the console output.

```bash
$ python packet_sniffer.py

```

```bash
$ python packet_sniffer.py -i eth0 -p 80
```

This will capture only HTTP packets on the eth0 interface and display information about each HTTP packet.
