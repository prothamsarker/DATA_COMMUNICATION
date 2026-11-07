
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

## Files

- `RIP_Presentation_Protham_Sarker.pptx`: the presentation slides
If you want, I can also add a “Key Concepts” section in the same style as the original once you send the part of the screenshot below that heading.

Ok make it and give me the final file. Also draw boxes like in the image

Created a file, shared files
Your final README.md is ready, in the same layout as your screenshot with your name, ID IT23027 and the 13-slide topic list.

The boxes come from the Markdown tables, which GitHub draws with borders and alternating row shading exactly like in your image. There are four boxed tables: Student Information, Key Concepts, RIP Versions at a Glance, and RIP vs OSPF vs EIGRP. I added the last three myself, so you can delete any of them if you want a shorter file.

To use it, upload README.md to the Presentation folder in your repository alongside the .pptx file. If it already has a README.md, replace that one.


Readme
Document · MD 
Give me like a text here. And where are the tables?

Checking how the README tables should render in chat.
The tables are in the README.md file, but you only see them as boxes after the file is on GitHub (or in a Markdown viewer). Opened as plain text, they look like rows of | symbols. Here is the full README as plain text with the tables showing as boxes:

Presentation on Routing Information Protocol (RIP)
Student Information
Field	Details
Name	Protham Sarker
Student ID	IT23027
Department	Information and Communication Technology (ICT)
University	Mawlana Bhashani Science and Technology University
Course	Data Communication
Course Code	ICT-3101
Course Teacher	Dr. Nazrul Islam, Associate Professor, Dept. of ICT, MBSTU
Presentation Topic	Routing Information Protocol (RIP)
Project Overview
This repository contains my academic presentation on Routing Information Protocol (RIP), prepared for the Data Communication course (ICT-3101).

RIP is one of the oldest dynamic routing protocols in computer networking. It lets routers share route information with their neighbours and choose the best path to a destination network by counting hops.

The presentation covers how RIP works, how it handles link failures and routing loops, its different versions, its strengths and limitations, and how it compares with OSPF and EIGRP.

Presentation Objectives
The main objectives of this presentation are:

Understand why networks need dynamic routing.
Explain how RIP works.
Understand hop count and routing tables.
Explore routing updates and convergence.
Learn how RIP controls routing loops.
Compare RIPv1, RIPv2, and RIPng.
Evaluate the strengths and limitations of RIP.
Compare RIP with OSPF and EIGRP.
Topics Covered
The presentation consists of 13 slides, covering the following topics:

Title
Roadmap
Why We Need a Routing Protocol
What Is RIP?
How a Router Learns Its Routes
Path Selection and a Routing Table
RIP at a Glance
Link Failures and Loop Control
RIPv1, RIPv2 and RIPng
RIP vs OSPF vs EIGRP
Strengths, Limits and Where RIP Fits
Key Takeaways and References
Thank You
Key Concepts
Concept	Meaning
Distance vector	Routers advertise reachable networks and their distance to neighbours
Hop count	The metric RIP uses; the fewest hops wins
Maximum hops	15 hops; a metric of 16 means unreachable
Update timer	Routing tables are advertised every 30 seconds
Convergence	The time routers take to agree on the network state after a change
Split horizon	A route is never advertised back out of the interface it was learned on
Route poisoning	A failed route is advertised with metric 16
Triggered updates	Changes are sent immediately instead of waiting for the timer
RIP Versions at a Glance
Feature	RIPv1	RIPv2	RIPng
Addressing	IPv4	IPv4	IPv6
Classless (CIDR)	No	Yes	Yes
Update delivery	Broadcast	Multicast	Multicast
Authentication	None	Supported	Relies on IPv6 security
UDP port	520	520	521
RIP vs OSPF vs EIGRP
Aspect	RIP	OSPF	EIGRP
Approach	Distance vector	Link state	Advanced distance vector
Metric	Hop count	Cost	Composite
Best suited to	Small networks	Large networks	Medium to large
Convergence	Relatively slow	Generally fast	Generally fast
Complexity	Low	Higher	Moderate
Selected References
RFC 1058: Routing Information Protocol (RIPv1)
RFC 2453: RIP Version 2
RFC 2080: RIPng for IPv6
RFC 4822: RIPv2 Cryptographic Authentication
