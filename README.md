IPv6 ACLs (STANDARD & EXTENDED BEHAVIOR)

LAB TOPOLOGY
-------------------------------------------
PC1 —— R1 —— R2 —— Server

IPv6 ADDRESSING PLAN
-------------------------------------------
LAN 1 (PC1 side)

2001:DB8:1:1::/64

PC1 → 2001:DB8:1:1::10

R1 G0/0 → 2001:DB8:1:1::1

R1–R2 Link

2001:DB8:12:12::/64

R1 G0/1 → 2001:DB8:12:12::1

R2 G0/0 → 2001:DB8:12:12::2

Server LAN

2001:DB8:2:2::/64

R2 G0/1 → 2001:DB8:2:2::1

Server → 2001:DB8:2:2::100
