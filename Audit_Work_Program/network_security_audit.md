# Network Security Audit Work Program

## 1. Objective
Evaluate security of network configurations, monitoring, and segmentation.

## 2. Risks
- Unauthorized access due to weak firewall rules.
- Lateral movement from poor segmentation.
- Undetected attacks due to insufficient monitoring.

## 3. Controls to Test
- Firewall configuration and rule review.
- IDS/IPS functionality.
- VLAN segmentation.
- VPN access control.
- Logging & monitoring of network events.

## 4. Detailed Test Procedures
### Firewall
1. Obtain firewall rule base.
2. Identify overly permissive rules (Any-Any).
3. Confirm rule review frequency.
4. Ensure NAT rules are properly documented.

### IDS/IPS
1. Validate sensor status.
2. Review blocked/detected events.
3. Confirm alerting is active and logs forwarded to SIEM.

### Network Segmentation
1. Review VLAN architecture.
2. Validate segmentation between user, server, and DMZ networks.

### VPN Access
1. Extract VPN user list.
2. Validate MFA enforcement.
3. Confirm inactive accounts are disabled.

## 5. Evidence Required
- Firewall export
- IDS logs
- Network diagrams
- VPN access logs

## 6. Expected Results
- Defined segmentation
- No insecure firewall rules
- Full IDS visibility

