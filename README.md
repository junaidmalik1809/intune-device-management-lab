# Microsoft intune-device-management-lab

This lab demonstrates Microsoft Intune usage for managing Windows 10 devices via compliance policies, configuration profiles, and app deployment.

## 🔧 Lab Objectives

- Create and manage Intune compliance policies
- Deploy device configuration profiles (e.g., USB restrictions)
- Assign Microsoft Store apps to users
- Monitor device and policy compliance

## 🧪 Lab Tasks Completed

### ✅ Test Users Created
Created the following test users in Microsoft Entra ID (Azure AD):
- `john.hr@yourtenant.onmicrosoft.com`
- `adam.it@yourtenant.onmicrosoft.com`
- `mary.marketing@yourtenant.onmicrosoft.com`

### ✅ Compliance Policy
- Policy name: `PasswordCompliancePolicy`
- Platform: Windows 10 and later
- Rules:
  - Require password to unlock device
  - Minimum password length: 6
- Assigned to: `john.hr` via security group

### ✅ Configuration Profile
- Profile name: `BlockUSBProfile`
- Type: Device restrictions
- Restrictions:
  - USB access: Blocked
  - Camera: (Optional) Disabled
- Assigned to: `adam.it` via security group

### ✅ App Deployment
- App: Microsoft To Do (Microsoft Store)
- Deployed to: `mary.marketing`

## 📸 Screenshots

See the `/screenshots` folder for:
- Users in Entra ID
- Compliance policy summary
- Configuration profile summary
- App deployment confirmation

## 🛠 Tools Used

- Microsoft 365 Business Premium Trial
- Microsoft Intune / Endpoint Manager
- Microsoft Entra ID (Azure AD)

---

## 📚 Outcome

This lab simulates real-world mobile device and endpoint management using cloud-native Microsoft Intune controls.
