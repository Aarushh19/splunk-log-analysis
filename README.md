# Splunk Log Analysis and Dashboarding (Log Monitoring Lab)

This project demonstrates how Splunk can be used to analyze web server logs (`access.log` and `error.log`) to extract insights, identify error patterns, and visualize server activity. The lab was conducted as part of my coursework in cybersecurity to build hands-on SIEM and log analysis skills.

---

## 🎯 Objective

Gain experience using Splunk to:
- Parse and analyze raw server logs
- Extract key fields (e.g., IP addresses, status codes)
- Build dashboards for real-time monitoring and visualization
- Detect access patterns and potential error spikes

---

## 🛠️ Tools & Setup

- **Splunk Enterprise (local instance)**
- **Log Files:** `access.log`, `error.log`
- Field extractions, search queries, and visualization panels

---

## 🔍 Key Activities

1. **Ingested Logs:**
   - Uploaded `access.log` and `error.log` into Splunk.

2. **Field Extraction:**
   - Used the “Extract New Fields” tool to isolate IP addresses and status codes.
   - Created custom fields for better filtering.

3. **Search Queries & Filters:**
   - Ran `stats count by status` and `stats count by error_IP_client`
   - Filtered by specific dates (e.g., Oct 7 & Oct 8) for comparison.

4. **Dashboard Creation:**
   - Built a custom dashboard showing:
     - Status code distribution pie chart
     - IP address frequency chart
     - Error trends over time

---

## 📸 Screenshots

> Update the image links below after uploading your screenshots

### ✅ Status Code Pie Chart
![Status Pie](https://raw.githubusercontent.com/Aarushh19/splunk-log-analysis/main/status-pie.png)

### ✅ Extracted IP Dashboard
![IP Chart](https://raw.githubusercontent.com/Aarushh19/splunk-log-analysis/main/ip-dashboard.png)

---

## ✅ Learning Outcomes

- Learned how to structure and visualize raw log data
- Practiced real-time search and event filtering
- Developed familiarity with SIEM tools for SOC environments

---

## ⚠️ Disclaimer

This lab was conducted in a controlled academic setting using simulated log files. All work was done for educational purposes only.

---

© Aarush Gupta | MS Cybersecurity & Privacy | University of Central Florida
