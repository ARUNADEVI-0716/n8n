# Appointment Booking Workflow (n8n)

This repository contains the exported **n8n workflow JSON** for an Appointment Booking System.  
The workflow integrates **Telegram**, **Google Sheets**, and **Stripe** to handle:

- Patient registration  
- Doctor appointment booking  
- Rescheduling & cancellations  
- Payment via Stripe or cash  
- Automated reminders  

---

## 🚀 How to Use

### Export Workflows
- In the n8n editor, open your workflow  
- Click **Download → Download JSON**  
- Save it into the `workflows/` folder of this repo  

### Version Control
- Commit workflow JSON files into GitHub  
- Every commit captures changes to your automation logic  
- Use Pull Requests for collaboration and reviews  

### Import Workflows
- In n8n editor → **Import from File**  
- Upload the JSON (e.g., `Appointment Booking.json`)  
- The workflow will be restored in your workspace  

---

## 📂 Repo Structure
├── workflows/
│ └── Appointment Booking.json
└── README.md
