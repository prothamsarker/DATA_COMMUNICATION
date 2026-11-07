
# Presentation on Routing Information Protocol (RIP)

---

## Student Information

| Field | Details |
|---|---|
| Name | Protham Sarker |
| Student ID | IT23027 |
| Department | Information and Communication Technology (ICT) |
| University | Mawlana Bhashani Science and Technology University |
| Course | Data Communication |
| Course Code | ICT-3101 |
| Course Teacher | Dr. Nazrul Islam, Associate Professor, Dept. of ICT, MBSTU |
| Presentation Topic | Routing Information Protocol (RIP) |

---

## Project Overview

This repository contains my academic presentation on **Routing Information Protocol (RIP)**, prepared for the Data Communication course (ICT-3101).

RIP is one of the oldest dynamic routing protocols in computer networking. It lets routers share route information with their neighbours and choose the best path to a destination network by counting hops.

The presentation covers how RIP works, how it handles link failures and routing loops, its different versions, its strengths and limitations, and how it compares with OSPF and EIGRP.

---

## Presentation Objectives

The main objectives of this presentation are:

- Understand why networks need dynamic routing.
- Explain how RIP works.
- Understand hop count and routing tables.
- Explore routing updates and convergence.
- Learn how RIP controls routing loops.
- Compare RIPv1, RIPv2, and RIPng.
- Evaluate the strengths and limitations of RIP.
- Compare RIP with OSPF and EIGRP.

---

## Topics Covered

The presentation consists of **13 slides**, covering the following topics:

1. Title
2. Roadmap
3. Why We Need a Routing Protocol
4. What Is RIP?
5. How a Router Learns Its Routes
6. Path Selection and a Routing Table
7. RIP at a Glance
8. Link Failures and Loop Control
9. RIPv1, RIPv2 and RIPng
10. RIP vs OSPF vs EIGRP
11. Strengths, Limits and Where RIP Fits
12. Key Takeaways and References
13. Thank You

---

## Key Concepts

| Concept | Meaning |
|---|---|
| Distance vector | Routers advertise reachable networks and their distance to neighbours |
| Hop count | The metric RIP uses; the fewest hops wins |
| Maximum hops | 15 hops; a metric of 16 means unreachable |
| Update timer | Routing tables are advertised every 30 seconds |
| Convergence | The time routers take to agree on the network state after a change |
| Split horizon | A route is never advertised back out of the interface it was learned on |
| Route poisoning | A failed route is advertised with metric 16 |
| Triggered updates | Changes are sent immediately instead of waiting for the timer |

---

## RIP Versions at a Glance

| Feature | RIPv1 | RIPv2 | RIPng |
|---|---|---|---|
| Addressing | IPv4 | IPv4 | IPv6 |
| Classless (CIDR) | No | Yes | Yes |
| Update delivery | Broadcast | Multicast | Multicast |
| Authentication | None | Supported | Relies on IPv6 security |
| UDP port | 520 | 520 | 521 |

---

## Selected References

- RFC 1058: Routing Information Protocol (RIPv1)
- RFC 2453: RIP Version 2
- RFC 2080: RIPng for IPv6
- RFC 4822: RIPv2 Cryptographic Authentication

---

