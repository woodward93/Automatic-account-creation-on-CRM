# Automatic-contact-creation-on-CRM
**🤝 HubSpot Contact Creation (n8n)**
This n8n workflow automatically creates new HubSpot contacts for users who recently signed up on an application. It pulls signup data from Redash or other user data sources, splits it into individual records, and adds each as a new contact in HubSpot with enriched metadata.

**🧩 Workflow Steps**

- **Schedule Trigger** – Runs periodically to check for new signups.

- **Get Signup Data** – Fetches new user data from Redash or other data sources.

- **Split Out** – Loops through each user record individually.

- **Create Users on HubSpot** – Sends user details (name, phone, email, or other custom properties) to HubSpot using an App Token.

**🔐 Required Setup**

| Credential            |           Purpose          |
| :-------------------- | :------------------------: | 
| **Redash API URL**    |  Source of new signup data | 
| **HubSpot App Token** | Authenticates API requests | 


**💡 Use Cases**
| Use Case                  |                     Description                     |                         Benefit |
| :------------------------ | :-------------------------------------------------: | ------------------------------: |
| **CRM Automation**        |        Syncs new users from your app into HubSpot and create a contact        | Keeps CRM updated automatically |
| **Lead Nurturing**        | Adds enriched contact details |      Enables targeted marketing |
| **Analytics Integration** |     Links HubSpot contacts to your app's user data     |   Supports performance tracking |



