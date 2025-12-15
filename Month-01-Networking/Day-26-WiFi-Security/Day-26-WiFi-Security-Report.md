# Day 26 — Wi-Fi Security Analysis

## 1. Objective
Analyze the security and behavior of a Wi-Fi network created using a mobile hotspot, evaluating connectivity, DHCP assignment, encryption modes, and client communication.

## 2. Materials / Equipment
- Mobile phone (hotspot)
- Secondary mobile device (client)
- Wi-Fi network (WPA2/WPA3 Mixed)

## 3. Lab Topology
- Hotspot device acting as Access Point
- Client device connected via Wi-Fi

## 4. Step-by-Step Development
### Step 1 — Hotspot activation
The mobile hotspot was enabled and a secondary device connected successfully.

### Step 2 — Network parameters verification
The client device received an IP address, subnet mask, gateway, DNS, and IPv6 address via DHCP.

### Step 3 — Client communication test
ICMP ping tests confirmed that client-to-gateway communication was allowed.

### Step 4 — Security mode evaluation
The hotspot provided WPA2, WPA3, and mixed security modes. The mixed mode was selected for compatibility and security.

### Step 5 — Security assessment
Strong password and modern encryption ensured a high security level for the network.

## 5. Evidence
- Hotspot configuration screenshots
- Network parameters on client device
- Ping test results

## 6. Issues Encountered
No internet access was available on the client device, which did not affect the internal network analysis.

## 7. Final Result
The Wi-Fi hotspot operated correctly with strong security and proper DHCP functionality.

## 8. Conclusion
This lab demonstrated how mobile hotspots implement modern Wi-Fi security mechanisms and how to analyze them safely in a controlled environment.
