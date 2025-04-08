## 🧪 osTicket Post Installation Configuration

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>


This phase focused on configuring the osTicket system to simulate a real-world helpdesk environment.

### ✅ Admin and Agent Access
- Admin Panel: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- End User Portal: [http://localhost/osTicket](http://localhost/osTicket)

### 🔧 Configuration Steps

- **Roles**: Created “Supreme Admin” role to define admin-level access.
- **Departments**: Created “SysAdmins” for ticket visibility and routing.
- **Teams**: Set up “Online Banking” team by pulling agents from various departments.
- **User Access Settings**:
  - Enabled registration/login requirement for ticket creation.

- **Agents**: Added Jane (SysAdmins) and John (Support).
- **Users**: Added Karen and Ken as end users.
- **SLA Policies**:
  - **Sev-A** (1 hr, 24/7)
  - **Sev-B** (4 hrs, 24/7)
  - **Sev-C** (8 hrs, Business Hours)
- **Help Topics**:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other

This gave me exposure to managing roles, access control, and how tickets can be routed based on severity and department.

---
