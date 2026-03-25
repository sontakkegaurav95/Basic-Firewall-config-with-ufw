# UFW Firewall Configuration

## Objective
To configure a basic firewall using UFW on Linux.

## Steps Performed
1. Installed UFW using apt
2. Allowed SSH (port 22)
3. Denied HTTP (port 80)
4. Enabled firewall
5. Verified rules using ufw status

## Commands Used
- sudo apt install ufw
- sudo ufw allow ssh
- sudo ufw deny http
- sudo ufw enable
- sudo ufw status verbose

## Output
Firewall is active with:
- SSH allowed
- HTTP denied

## Conclusion
Successfully configured a basic firewall using UFW.
