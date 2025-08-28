# Windows Domain & Active Directory

---

## 1. Active Directory Overview
- **Active Directory (AD)**: Centralized repository to control and configure all systems under a domain.  
- **Domain Controller (DC)**: Server in charge of managing AD.  
- Provides **centralized control** for authentication, authorization, and policies.  

<img src="https://github.com/user-attachments/assets/0ee68bcc-2392-4807-aee7-6f82dec1611e" width="600" />

---

## 2. Organizational Units (OUs)
- OUs can be created to **separate users by departments**.  
- **Users**: Belong to one OU at a time (policies are applied per OU).  
- **Security Groups**: Users can belong to many groups (to access multiple resources).  

<img src="https://github.com/user-attachments/assets/6f8c8478-b258-4362-80f9-abde13b25a8c" width="600" />

---

## 3. Administration & Delegation
- **Domain Admins**: Responsible for administering all computers and resources in the domain.  
- `$` → used to associate **machines with accounts**.  
- Deleting an OU may require:  
  - Enabling **Advanced Features** view.  
  - Removing "Protect object from accidental deletion".  
- **Delegation**:  
  - Control can be delegated to specific users for OUs.  
  - Example: Delegating Philip password reset permissions.  

<img src="https://github.com/user-attachments/assets/85114afb-c5a9-4887-a87b-1a8b9d7e670a" width="600" />  
<img src="https://github.com/user-attachments/assets/96f8977c-4263-4f3f-945c-5c053762bdfd" width="600" />

---

## 4. Group Policy Objects (GPOs)
- **Group Policy Management (GPM)**: Used to configure domain-wide policies.  
- **Assigned to OUs** to enforce security, updates, or restrictions.  
- Examples:  
  - Automatic updates.  
  - Password policies.  
  - Device inactivity lock (e.g., 300 seconds).  
  - Restrict access to Control Panel.  
- **SYSVOL**: Network share that distributes GPOs across domain controllers.  

<img src="https://github.com/user-attachments/assets/6efcb295-4c16-40a3-b222-1625ae1858e6" width="600" />  
<img src="https://github.com/user-attachments/assets/304f3148-7e85-44c7-a67f-056b03b38e5a" width="600" />  
<img src="https://github.com/user-attachments/assets/2378e624-d386-41d4-9477-8ee73237a604" width="600" />

---

## 5. Authentication Protocols
- **Kerberos Authentication**  
  - Ticket-based authentication system.  
  - Default and more secure in Windows domains.  

<img src="https://github.com/user-attachments/assets/a5a350b1-fda6-4cff-8f9e-eb903f5ae640" width="600" />

- **NetNTLM Authentication**  
  - Challenge-response protocol.  
  - Older, less secure, but still supported in some environments.  

<img src="https://github.com/user-attachments/assets/a4d8d11e-48c8-428a-b6fd-c2ab313cdfff" width="600" />

---

## 6. Scalability
- Large organizations may have **multiple domain controllers** by country/region.  
- **Forests**: Multiple domains joined together.  
- **Trust Relationships**: Define how domains interact.  
  - Example: **One-Way Trust** → one domain trusts another, but not vice versa.  

<img src="https://github.com/user-attachments/assets/82df4fbf-a158-481a-b957-31ad86ee74b3" width="600" />  
<img src="https://github.com/user-attachments/assets/4b70ce27-e289-44b2-8912-3bb7f4e1b2c4" width="600" />

---

## 7. Best Practices
- **Organize workstations, DCs, and servers** logically → avoid dumping all machines in the "Computers" section.  
- Apply policies at the OU level for **granular control**.  
- Regularly **tidy up AD structure** for scalability and clarity.  

<img src="https://github.com/user-attachments/assets/3999f6d6-2a23-4181-9093-84a741ca36ce" width="600" />






























