# Job Radar
**An AI-assisted platform for discovering, prioritizing and tracking job opportunities.**

🔗 **Live Demo:** [Job Radar](https://buzzz001.github.io/job-radar/)

![Job Radar Dashboard](dashboard.png)

---

## Overview
Job Radar is an automation platform that aggregates relevant job opportunities from multiple sources like company career pages and ATS pages into a single dashboard.
I built it to speed up my job-hunting process, while also learning workflow automation with n8n.

---

## Features
### Job Discovery
- Aggregates jobs from Greenhouse, Lever, Ashby, Workable, and selected third-party job boards
- Normalizes job data from multiple ATS platforms into a consistent format
- Detects duplicate jobs based on posting URLs
### Search & Filtering
- Keyword search with partial matching
- Filter by posting date, status and category
- Remote and location tags
- Multi-dimensional job scoring
### Application Tracking
- Mark jobs as **Applied**, **Saved**, or **Not for Me**
- Automatically syncs status changes to Google Sheets
### Dashboard & Monitoring
- Interactive dashboard for browsing opportunities
- Manual data refresh
- Displays latest refresh timestamp
- Source Health tab in the sheet for monitoring workflow and connector errors
- Rejected Jobs tab in the sheet for reviewing discarded opportunities

---

## Future Improvements
- Improve the job scoring algorithm
- Support additional ATS platforms and job boards
- Add pagination as the number of tracked jobs grows
- Improve duplicate detection
- Resume-to-job matching
- Enhanced filtering and analytics
