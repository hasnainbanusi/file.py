# 📊 Log Analyzer Tool

A lightweight, efficient Bash script designed to parse and analyze web server logs (Apache/Nginx). This tool demonstrates the power of core Linux utilities for rapid troubleshooting and security auditing.

## 🚀 Features
- **Total Request Counter:** Get a quick bird's-eye view of your traffic volume.
- **Top IP Identification:** Automatically lists the top 5 most active IP addresses using `awk` and `uniq`.
- **Error Tracking:** Specifically filters and counts `404 Not Found` errors using `grep`.
- **Status Code Summary:** Extracts and sorts all unique HTTP status codes present in the log file.

## 🛠️ Tech Stack
- **Language:** Bash Scripting
- **Utilities:** `grep`, `awk`, `sed`, `sort`, `uniq`

## 📋 How to Use
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Hasnain-Banusi/log-analyzer-tool.git](https://github.com/Hasnain-Banusi/log-analyzer-tool.git)
   cd log-analyzer-tool
