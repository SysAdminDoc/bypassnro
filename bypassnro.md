# Windows 11 Insider Build Removes Bypass Script for Local Account Setup

Microsoft released a new Windows Insider build of Windows 11 to its experimental **Dev Channel**, with a fairly extensive batch of new features and tweaks.

But the most important change for enthusiasts and PC administrators is buried halfway down the list:

> **This build removes a command prompt script called `bypassnro`**, which up until now has been a relatively easy and reliable way to circumvent the mandatory Microsoft Account sign-in requirement on new Windows 11 PCs and fresh installs.

---

## 🔧 Here's How to Continue Getting Around It

1. Press `Shift + F10` during setup to open a command prompt.
2. Run the following command:

https://github.com/user-attachments/assets/67850d9c-93b6-43f4-b5b8-cc7c1f23db23

> 📁 This was found by examining:
> `C:\Windows\SystemApps\Microsoft.Windows.CloudExperienceHost_cw5n1h2txyewy\data\prod\navigation.json`
