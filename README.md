# VXLAN Student Guide

**Author:** Asad Yaseen
**Contact:** asad4ntrp2@gmail.com

A comprehensive guide covering VXLAN fabric technology from Layer 2 fundamentals through advanced data center and campus fabric architectures. Designed for network engineers, students, and professionals preparing for consultant-level interviews.

## What's Inside

This guide walks through the full journey from traditional VLANs to modern VXLAN fabrics:

- **Layer 2 Fundamentals** - VLANs, CAM tables, First Hop Redundancy Protocols
- **VXLAN Concepts** - VXLAN fundamentals, VLAN vs VXLAN comparison
- **Fabric Architecture** - Clos/Leaf-Spine architecture, Underlay and Overlay networks
- **Control Plane** - BGP EVPN fundamentals and route types
- **Traffic Flow** - Intra-VXLAN, Inter-VXLAN routing, BUM traffic handling
- **Multicast in VXLAN** - Multicast groups, VNI-to-multicast mapping strategies
- **Anycast Gateway** - Distributed gateway as FHRP replacement
- **Vendor Implementations** - Cisco DNA/SD-Access and Juniper Campus Fabric
- **External Connectivity** - Fusion router integration and external traffic flow
- **Hands-On Labs** - Step-by-step labs for Cisco (NX-OS, DNA Center) and Juniper
- **Interview Preparation** - Questions and answers from basic to consultant level

## Files

| File | Description |
|------|-------------|
| `learning.md` | Main student guide with all concepts, diagrams, and configuration examples |
| `VXLAN_Student_Guide.html` | Interactive HTML version with styled layout, clickable table of contents, and color-coded sections |
| `VXLAN_Diagrams.drawio` | Draw.io file with multi-sheet diagrams covering fabric topology, traffic flows, and architecture |
| `continue.md` | Project progress tracking and version history |

## How to Use

- **Beginners**: Start from Part I and build your Layer 2 foundation before moving forward
- **Intermediate**: Focus on Parts III, IV, and V to understand fabric architecture and traffic flow
- **Advanced**: Deep dive into Parts VI-IX for multicast, anycast, and vendor-specific implementations

Open the HTML file in any browser for the best reading experience with navigation, styling, and visual diagrams.

## Lab Environments

The hands-on labs can be run using:
- GNS3 or EVE-NG
- Cisco VIRL/CML
- Juniper vMX/vQFX

## Topics Covered

| Area | Technologies |
|------|-------------|
| Layer 2 | VLANs, MAC addresses, CAM tables, STP |
| Overlay | VXLAN, VNIs, VTEPs, NVE interfaces |
| Control Plane | BGP EVPN, Route Types 1-5 |
| Architecture | Clos, Leaf-Spine, Underlay/Overlay |
| Vendors | Cisco NX-OS, DNA Center, Juniper Junos |
| Integration | Fusion routers, external connectivity |

## License

This project is provided for educational purposes.
