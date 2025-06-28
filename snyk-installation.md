
---

### ⚙️ `snyk-installation.md`

```markdown
# Snyk Container Installation & Usage Guide

## 🔧 Installation Steps

1. Create an account at: https://app.snyk.io
2. Visit your CLI setup page to get the token:  
   https://app.snyk.io/account

3. Install CLI:

```bash
curl https://static.snyk.io/cli/latest/snyk-linux -o snyk
chmod +x snyk
sudo mv snyk /usr/local/bin/


## Authenticate


# Use the token from your Snyk account:

snyk auth <token>

# Scan command:

snyk container test nginx:latest --org=<your-org-id>
