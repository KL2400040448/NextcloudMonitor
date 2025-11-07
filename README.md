# 🌐 Nextcloud Server Connectivity Test

A simple PowerShell script to check the **network and web availability** of your Nextcloud server.

---

## 🚀 Features

✅ Ping test – Verifies if the server is reachable on your local network  
✅ Web test – Checks if the Nextcloud web interface responds (HTTP 200)  
✅ Color-coded status output (Green = OK, Yellow = Warning, Red = Error)  
✅ Lightweight and runs continuously if desired  

---

## ⚙️ How It Works

1. The script pings your server to test **basic connectivity**.  
2. If the ping succeeds, it sends an HTTP request to confirm **web access**.  
3. Results are displayed in color for easy reading.

---

## 💻 Run the Script

```powershell
# Clone or download the repository
git clone https://github.com/KL2400040448/NextcloudMonitor.git
cd NextcloudMonitor

# Run the PowerShell script
.\NextcloudMonitor.ps1
