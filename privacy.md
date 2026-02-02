# **Privacy Policy for SheepO User Watcher**

**Last Updated:** 01/22/2026

## **1\. Introduction**

SheepO User Watcher ("the Extension") is designed to help Microsoft 365 administrators view and export user, group, and audit log data. We value your privacy and are committed to protecting your data. This policy outlines how we handle your information.

## **2\. Data We Collect and How We Use It**

### **A. Microsoft 365 Data (Users, Groups, Audit Logs)**

The Extension accesses your Microsoft 365 tenant data via the Microsoft Graph API.

* **Purpose:** To display user lists, group memberships, and audit logs within the Extension's dashboard and to allow you to export this data to a local spreadsheet.  
* **Storage:** This data is fetched directly from Microsoft to your browser. **We (the developers) do not collect, store, transmit, or have access to this data.** It remains strictly within your local browser instance and your Microsoft tenant.

### **B. Authentication Data**

The Extension uses OAuth2 via `chrome.identity` to authenticate you with Microsoft.

* **Purpose:** To verify your identity and grant the Extension permission to access the data you requested.  
* **Storage:** Authentication tokens are stored securely within the browser's local storage and are used solely for communicating with the Microsoft Graph API.

### **C. User Preferences**

The Extension saves your display preferences (e.g., selected columns, filter settings) locally using the Chrome Storage API.

* **Purpose:** To improve user experience by remembering your settings between sessions.

## **3\. Third-Party Services**

The Extension communicates directly with the following third-party service:

* **Microsoft Graph API:** Used to fetch your M365 data. Use of this data is subject to [Microsoft's Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement).

## **4\. Data Sharing and Disclosure**

We do not sell, trade, or otherwise transfer your data to outside parties. Since the Extension operates as a client-side tool, your M365 data is never transmitted to our servers.

## **5\. Your Rights**

Since we do not store your data on our servers, you retain full ownership and control. You can revoke the Extension's access to your Microsoft account at any time via your Microsoft 365 account privacy settings.

## **6\. Contact Us**

If you have questions about this Privacy Policy, please contact us at: [support@ifebdevs.com](mailto:support@ifebdevs.com)

