## Welcome to the Github page of the Networks and Distributed Systems Group

### Ongoing Work related to SCION

- [Support for Peering Links](https://github.com/scionproto/scion/pull/4299)
- [SCION Certificate Authority](https://github.com/netsys-lab/scion-ca) and
  [renew service for endhosts](https://github.com/netsys-lab/scionlab-cert-renewer)
- [ID-INT](https://github.com/netsys-lab/id-int-spec)
- Border router improvements
    - Make the Go reference border router's data plane exchangeable to allow
      using hardware implementations like the Tofino or XDP from the Go code
    - BPF implementation of SCION Border Router
    - Implement AF_XDP as interface between XDP router and Go control plane
    - Splitting the border router's AES-CMAC validation and forwarding mechanisms
      to allow more flexible implementation in hardware
- Extend the [SEED Emulator](https://github.com/seed-labs/seed-emulator) with
  P4/Tofino support
- [BitTorrent over SCION](https://github.com/netsys-lab/bittorrent-over-scion)
  improvements and GUI
- DNS-over-QUIC support for SCION
- IPFS over SCION, SCION support in libp2p
- [Hercules](https://github.com/netsec-ethz/hercules) ongoing work and improvements
- Deadline-aware Multipath Transport Protocol
- [Scriptable path selector](https://github.com/netsys-lab/pan-lua)
- Evolutionary Multi-objective optimization for optimal path selection
- Bitcoin over SCION - Resilience against partitioning and other routing attacks
- Beacon filtering

### Completed Work

- [DDoS Detection](https://github.com/netsys-lab/ddos-detection-sketches-p4)
  in P4 Using HyperLogLog and CountMin Sketches
- [SCION Peering Coordinator](https://github.com/netsys-lab/scion-peering-coordinator)
  ([paper](https://journal.ub.tu-berlin.de/eceasst/article/view/1159))
- [SCION and In-band Network Telemetry Layers for Scapy](https://github.com/lschulz/scapy-scion-int)
- [SCION support in SEED Emulator](https://github.com/seed-labs/seed-emulator/pull/143)
- [PAN bindings](https://github.com/lschulz/pan-bindings) for C, C++ and Python
