# 📊 Server Performance Optimization Dashboard
# 🗓️ Date Range: June 28 - June 30
This dashboard provides key performance insights of servers over a 3-day period to help IT teams monitor and optimize server infrastructure.

# 📌 Features
✅ Interactive Filters by Server (A, B, C)

🧠 Memory and CPU Utilization Summary

⚙️ Disk Read/Write (MB/s) by Day

🌐 Network In vs Network Out (MB) Analysis

⏱️ Average Response Time (ms)

⏳ Average Uptime (Hours & Minutes)

❌ Count of Errors by Day

📷 Dashboard Snapshot

# 💡 Technologies Used
Power BI – For data modeling, visualization, and interactivity

MySQL – As the backend database for storing and retrieving server logs and performance metrics

# 📈 Insights
Highest Disk Read observed on June 29 with 594 MB/s.

Average Response Time increased from 297 ms (June 28) to 313 ms (June 30).

Server A encountered 21 errors over the 3-day span.

Network In/Out patterns indicate intermittent spikes, possibly during peak operations.

# Observations & Insights
# Server A
✅ Best in CPU usage (Lowest).
✅ Fewest errors (Only 21).
⚠️ Higher response time on Day 30 (313 ms).
⚖️ Balanced read/write, moderate network usage.

# Server B
⚠️ Highest error count (25).
✅ Best response time on Day 29 (273 ms).
⚠️ Slightly higher CPU usage than A.
⚖️ Moderate disk activity and network performance.

# Server C
⚠️ Highest total errors (28).
✅ Lowest disk write (efficient use).
✅ Balanced and stable network in/out.
⚠️ Moderate CPU usage but not best performing.

# Conclusions & Recommendations
 Best Overall Performing Server: Server A
 Why? Lowest CPU, lowest error count, stable performance.

️ Server B Needs Attention On:
 Error handling: High number of consistent errors (10, 10, 5).
 CPU usage creeping up — investigate resource-heavy processes.

⚠️ Server C Needs Immediate Review:
    Highest errors (8, 7, 13) — especially Day 30.
    Slightly worse response time trend.
    Disk performance seems solid, but high error rate is a concern.


# Dashboard Review -
