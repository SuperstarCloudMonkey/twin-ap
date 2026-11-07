# TwinNet

Experimental Windows desktop app for timed internet pauses by device name across two local networks.

Windows executable packaging is in progress. This repository is not yet a verified release.

The app uses local ARP/NDP redirection and requires the official Npcap driver, administrator rights, and one network adapter on each LAN. It preserves directly connected local traffic where the network supports this technique. IPv6, private MAC changes and router protections can bypass a pause. Test on each device; this is not a tamper-proof access-control system.

No router credentials, household configuration or browsing history are included.
