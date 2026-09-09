
---

# 4. `04_FIM/fim_configuration.md`

```markdown
# File Integrity Monitoring Configuration

## Overview

File Integrity Monitoring, also known as FIM, is used to monitor files and directories for changes.

Wazuh can detect events such as:

- File creation
- File modification
- File deletion
- File size changes
- Modification time changes
- Hash changes

For this lab, I configured Wazuh to monitor a folder on my Windows 11 system.

---

## Monitored Directory

The directory used for testing was:

```text
C:\Users\HP USER\SensitiveFile