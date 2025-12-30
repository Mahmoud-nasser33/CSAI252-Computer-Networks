## University Campus Network Design Project

## Course Information
Course: Introduction to Computer Networks - Fall 2024
Institution: Zewail City of Science and Technology
Course Code: CSAI 252

## Team Members
Mahmoud Sakr -
Rawda Mohammed -
Eman Taia -
Nourhan Samir -

## Supervised By
Professor: Dr. Heba Aty -
Teaching Assistants: Ahmed Abdelgawad, Hana Zein

## Project Description
Design a network for a university campus with 4 faculties and 1 Scientific Computation Center.
Each faculty has 4 floors.
Each floor has 5 labs.
Each lab has 10 PCs connected to switches.
Network Components
PCs: 10 per lab connected via switches
Switches: Used at lab level, floor level, and faculty level
Routers: Connect faculties together and to the internet
Servers: Located in Scientific Computation Center
IP Addressing
First Faculty: 192.168.1.0
Second Faculty: 192.168.2.0
Third Faculty: 192.168.3.0
Fourth Faculty: 192.168.4.0
DNS Server: 192.168.1.2
VLAN Configuration
First Faculty: VLAN 10 (CIE), VLAN 20 (CS)
Second Faculty: VLAN 10 (Management), VLAN 20 (Office Hours)
Third Faculty: VLAN 10 (Staff), VLAN 20 (TAs)
Fourth Faculty: VLAN 10 (BIS), VLAN 20 (Doctors)
Features
Classless IP addressing
Star and Mesh topology
VLAN segmentation
DNS configuration
Test scenarios
RIP Routing Protocol (Bonus)
