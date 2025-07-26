# mssecuritynews

**mssecuritynews** is a set of Power Automate flows that fetch the latest Microsoft Security News from various sources directly into your Teams chat or channels. It aggregates content from:

- Microsoft Tech Community blogs  
- Microsoft Learn "What's New" pages (some is not working properly yet) 
- Official Microsoft Security YouTube channels  
- Microsoft Security Twitter/X accounts
- Roadmap pages both M365 abd Azure

It uses both official RSS feeds and custom-generated ones to ensure wide coverage.

## 🛠 Setup Guide (Dataverse import method, I'll add legacy method later)

### Prerequisites (Dataverse method)

- A Microsoft tenant    
- At least Business Premium license 
- At least Power Platform admin role to create databse (if it dont exist) 
- A Dataverse database, read more about prerequisites here for Dataverse here [https://learn.microsoft.com/en-us/power-platform/admin/create-database?tabs=new](https://learn.microsoft.com/en-us/power-platform/admin/create-database?tabs=new)


📦 Import Method

1. Go to [https://powerautomate.com](https://powerautomate.com)
2. Navigate to **My Flows → Import → Import Solution**
   - ⚠️ If you don’t have a Dataverse database, Power Automate will prompt you to create one. Follow the instructions and wait ~5 minutes before proceeding.
3. Go to **Solutions → Import Solution**
   - Upload the provided `.zip` file that contains the flows and configurations.
4. Press **Next → Next → Import** to begin.
5. Wait for the message:
   > ✅ "Solution 'Microsoft Security News' imported successfully"
6. Open the imported **Solution**.
7. Go to the **Cloud flows** tab and open any of the flows.
8. Click **Edit**, scroll to the **"Alert the team"** step, and choose your preferred **Teams chat or channel**.
9. Repeat the above step for all flows (if desired).
10. Once configured, select all flows and click **"Turn On"** to activate them.

---

## 🔐 Note on Permissions

These flows run using **your Microsoft account credentials**

---

## 📬 Feedback / Issues

If you encounter bugs or want to suggest improvements, feel free to [open an issue]

