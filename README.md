# ServiceNow Lab Project: User Access Troubleshooting via Impersonation

## 🎯 Objective
Diagnose and resolve an end-user navigation issue regarding password management settings using ServiceNow administrative tools, without compromising user account security.

## 🛠️ Tools & Modules Used
* **ServiceNow Developer Instance**
* **Impersonate User Feature** (System Administrator control)
* **Application Navigator & Favorites** (UI personalization)

## 📋 Step-by-Step Implementation

### Step 1: Simulate the Incident
* **Scenario:** An end-user reported being unable to find or access the settings required to change their password within the portal interface.
* **Action:** Logged into the ServiceNow Personal Developer Instance (PDI) with `admin` credentials to review system configuration.

### Step 2: Utilize the Impersonate User Tool
* **Action:** Clicked on the user profile icon in the top-right banner, selected **Impersonate User**, and selected the affected test user account. 
* **Purpose:** This allowed me to view the instance exactly as the end-user sees it, ensuring permission levels matched their experience.

### Step 3: Troubleshoot and Optimize UI Navigation
* **Action:** While impersonating the user, used the **Filter Navigator** to locate the "Password Reset" module.
* **Enhancement:** Clicked the star icon next to the module to add it to the user's **Favorites** for streamlined access.

### Step 4: UI Personalization
* **Action:** Navigated to the Favorites section to edit the favorite entry.
* **Customization:** Assigned a distinct color scheme and selected a key icon to improve visual clarity and user experience.

### Step 5: Verification and Session Closeout
* **Action:** Ended the impersonation session, confirming that administrative control was restored and the user environment was successfully optimized.

## 💡 Business Value & Key Takeaways
* **Security Best Practice:** Demonstrated the ability to troubleshoot user-specific issues securely via impersonation, eliminating the risky practice of handling user passwords.
* **User Adoption & UX:** Showed how proactive UI personalization (favorites, icons) reduces user friction and cuts down on repetitive IT service desk tickets.
