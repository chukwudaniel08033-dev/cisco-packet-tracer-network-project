# Cisco Packet Tracer Network Project — Evidence

## Project overview
This project documents a small Cisco Packet Tracer network with two PCs connected to a switch and a router. The evidence also includes connectivity tests and a Google-style homepage displayed in the Packet Tracer PC web browser.

## Evidence files
- `evidence/01-network-topology.png` — two PCs, a switch, and a router in the topology.
- `evidence/02-successful-ping-192-168-0-3.png` — successful ping replies from `192.168.0.3`.
- `evidence/03-ping-tests-and-addressing-check.png` — shows successful replies from `8.8.8.8` in the simulation and a failed ping to `192.168.1.2`.
- `evidence/04-google-style-homepage.png` — Google-style homepage displayed in the Packet Tracer browser.

## Notes and limitations
- The failed ping to `192.168.1.2` suggests an IP addressing mismatch with the `192.168.0.x` network shown in the other test. Verify both PCs' IP addresses, subnet masks, and default gateways before claiming all LAN tests pass.
- A successful ping to `8.8.8.8` in Packet Tracer only shows that a device at that address responded in this simulation; it does not prove access to Google's real public DNS service or the public Internet.
- The browser screenshot shows a Google-style homepage. It does not establish that the real Google website is being served by the project.
- The Cisco Packet Tracer `.pkt` project file was not included in the supplied evidence. Add your `.pkt` file to the repository separately if you want others to open and inspect the network.

## Suggested GitHub repository description
Cisco Packet Tracer practice project demonstrating a two-PC LAN, switch/router topology, ping testing, and a simulated web homepage.

## Suggested repository structure
```text
cisco-packet-tracer-project/
├── README.md
└── evidence/
    ├── 01-network-topology.png
    ├── 02-successful-ping-192-168-0-3.png
    ├── 03-ping-tests-and-addressing-check.png
    └── 04-google-style-homepage.png
```
