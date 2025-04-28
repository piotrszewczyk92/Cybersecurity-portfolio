## Windows Firewall Project

### Block Remote Rule

**Project Description:**
In this project, I created a custom inbound rule in **Windows Defender Firewall with Advanced Security** to **block unauthorized remote connection attempts** to my system.
The goal was to enhance system security by limiting potential attack surfaces related to remote access.

**Steps Taken:**
1. Opened **Windows Defender Firewall with Advanced Security** (`wf.msc`).
2. Selected **New Inbound Rule**.
3. Configured:
- **Rule Type**: (Port / Program / Custom) *(depending on specifics)*.
- **Protocol and Ports**: (e.g., TCP port 3389 for Remote Desktop Protocol – if applicable).
- **Action**: **Block the connection**.
- **Profile**: Domain, Private, and/or Public.
4. Named the rule **Block Remote**.
5. (Optional) Added a description.
6. Clicked **Finish** to apply.

**Purpose:**
- To block incoming remote connections and strengthen system security.

**Skills Developed:**
- Firewall rule management
- Network security basics
- Hands-on experience with Windows security configurations
