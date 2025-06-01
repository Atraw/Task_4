# Task 4: Setup and Use a Firewall on Windows

## Steps Taken

1. **Opened Windows Defender Firewall with Advanced Security.**
2. **Listed current firewall rules (see screenshot).**
3. **Added a rule to block inbound traffic on port 23 (Telnet).**
4. **Tested the rule by attempting to connect to port 23 locally (see screenshot).**
5. **(Optional) Added a rule to allow inbound traffic on port 22 (SSH).**
6. **Removed the test block rule.**
7. **Documented steps and commands.**

## Screenshots

- `current_rules.png`
- `block_port_23_rule.png`
- `telnet_test.png`
- `allow_ssh_rule.png` (optional)
- `rule_deleted.png`

## Interview Questions (Sample Answers)

1. **What is a firewall?**  
   A firewall is a network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules.
2. **Difference between stateful and stateless firewall?**  
   Stateful firewalls track active connections and make decisions based on context; stateless firewalls filter packets based on static rules.
3. **What are inbound and outbound rules?**  
   Inbound rules control incoming traffic; outbound rules control outgoing traffic.
4. **How does UFW simplify firewall management?**  
   UFW (Uncomplicated Firewall) provides a simple command-line interface for managing firewall rules on Linux.
5. **Why block port 23 (Telnet)?**  
   Telnet transmits data in plaintext, making it insecure.
6. **What are common firewall mistakes?**  
   Overly permissive rules, not updating rules, and not monitoring logs.
7. **How does a firewall improve network security?**  
   It prevents unauthorized access and controls network traffic.
8. **What is NAT in firewalls?**  
   Network Address Translation (NAT) allows multiple devices to share a single public IP address.
