
---

### 🛡 `grype-installation.md`

```markdown
# Grype Installation & Usage Guide

## 🔧 Installation on Ubuntu

```bash
curl -sSfL https://raw.githubusercontent.com/anchore/grype/main/install.sh | \
  sh -s -- -b /usr/local/bin

## Scan image command

grype nginx:latest
