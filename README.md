# Communication-Network-Simulations

Hands-on network topologies and configs built in **Cisco Packet Tracer**.  
Focus: VLANs, inter-VLAN routing, dynamic routing (RIP/OSPF), IP planning, and secure segmentation.

## 📁 Repository Structure
- `pkt/` – Packet Tracer project files (`.pkt`)
- `configs/` – Router/Switch startup configs (`.txt`)
- `docs/` – Diagrams, notes, design PDFs
- `scripts/` – Helpers (e.g., IP calculators)
- `images/` – Screenshots for the README

## 🚀 Featured Topologies
1. **Campus VLAN + Inter-VLAN Routing**
   - Multiple VLANs (10/20/30), trunk links, ROAS or L3-SVI
   - Inter-VLAN and DHCP relay verification
2. **Multi-Router OSPF**
   - Single-area OSPF, loopback ads, route verification
3. **Secure Segmentation**
   - ACLs to restrict inter-dept traffic

## ✅ How to Use
1. Open `.pkt` files in **Cisco Packet Tracer** (prefer v8.x+).
2. Check `configs/` for device startup configurations.
3. Follow `docs/` for IP plan and topology diagrams.

## 🧪 Verification Checklist
- VLANs created & access ports assigned
- Trunks with allowed VLAN list
- Inter-VLAN routing (ROAS or L3 switch)
- OSPF neighbors up, routes learned
- ACLs applied to correct direction/interface

## 🛠️ Tools
- Cisco Packet Tracer (8.x)
- Optional: draw.io / diagrams.net for topology diagrams
- Python 3.x for IP helper scripts

## 📄 License
MIT License — see `LICENSE`.

