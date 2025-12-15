# Day 27 — Home Cybersecurity Lab (Kali + Ubuntu)

## 1. Objective
Create and validate an isolated home cybersecurity lab using Kali Linux as the attacker machine and Ubuntu as the victim machine.

## 2. Materials / Equipment
- VirtualBox
- Kali Linux (Attacker)
- Ubuntu Linux (Victim)
- Host-Only network

## 3. Lab Topology
- Kali Linux — 192.168.56.101
- Ubuntu Linux — 192.168.56.102
- Network: 192.168.56.0/24 (Host-Only)

## 4. Step-by-Step Development
### Step 1 — Network configuration
Both virtual machines were configured using a Host-Only network adapter to ensure isolation.

### Step 2 — IP address verification
IP addresses were obtained using the `ip a` command on both machines.

### Step 3 — Connectivity test
Bidirectional ICMP ping tests confirmed communication between attacker and victim machines.

### Step 4 — Role assignment
Kali Linux was assigned as the attacker machine, while Ubuntu acted as the victim.

### Step 5 — Routing verification
Routing tables confirmed that both machines belonged to the same isolated network segment.

## 5. Evidence
- VirtualBox network configuration screenshots
- Output of `ip a` on both machines
- Successful ping test results

## 6. Issues Encountered
Initial lack of IP assignment when using an internal network without DHCP was resolved by switching to a Host-Only adapter.

## 7. Final Result
A fully functional and isolated cybersecurity lab was successfully created and validated.

## 8. Conclusion
This lab established a safe and controlled environment for future cybersecurity practices such as scanning, enumeration, and vulnerability analysis.
