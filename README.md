# Task 8: Working with VPNs

# Objective
Understand the role of VPNs in protecting privacy and ensuring secure communication online.
# Tools Used
ProtonVPN (Free Tier)
Windscribe (Free Tier)
whatismyipaddress.com (to verify IP change)

# Steps Performed
# 1 Choose a VPN Service
Signed up for ProtonVPN Free (alternative: Windscribe Free).
Created a free account using email verification.
## 2 Download & Install VPN Client
Downloaded ProtonVPN from the official site.
Installed on the system.
```bash
sudo apt update
sudo apt install protonvpn
```
# 3 Connect to a VPN Server
Logged into ProtonVPN client.
Selected the closest available free server.
Successfully connected (status indicator showed active).
# 4 Verify IP Address Change
Checked IP on whatismyipaddress.com.
IP changed from ISP-assigned to VPN server IP.
# 5 Confirm Encrypted Traffic
Browsed websites while connected.
Traffic encrypted through VPN tunnel + HTTPS.
# 6 Disconnect & Compare
Disconnected from VPN.
IP reverted to ISP’s real IP.
Browsing speed slightly improved after disconnect.
# 7 Research on VPN Security
VPNs typically use AES-256 encryption with OpenVPN, WireGuard, or IKEv2/IPSec.
Prevents ISP tracking, unsafe public Wi-Fi interception, and IP-based tracking.
Free VPNs have limitations (speed, servers, possible logging).
# 📖 Summary
# ✅ Benefits
Encrypts all network traffic (safe on public Wi-Fi).

Masks real IP address → increases anonymity.

Bypasses geo-blocks and censorship.

Stops ISP from monitoring browsing.

# ⚠️ Limitations
Free plans = speed/data/server restrictions.

Some providers may log user data.

Encryption overhead can reduce performance.

VPN ≠ replacement for HTTPS or end-to-end encryption.
