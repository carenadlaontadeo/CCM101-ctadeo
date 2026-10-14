# Firewall Configuration

## 1. Allow SSH

```bash
sudo ufw allow ssh
```

This command allows SSH traffic so administrators can remotely manage the server.

## 2. Set the Default Firewall Policies

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

The first command blocks incoming traffic by default, while the second allows outgoing traffic from the server.

## 3. Enable the Firewall

```bash
sudo ufw enable
sudo ufw status verbose
```

These commands activate the firewall and display its current status and default policies.

## 4. Allow Port 8080

```bash
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

These commands allow TCP traffic on port 8080 and display the numbered firewall rules.

## 5. Note

If `sudo ufw enable` is executed before `sudo ufw allow ssh`, remote administrators may lose their SSH connection because the firewall could block the traffic needed to manage the server.
