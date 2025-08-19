
# NexDial Admin Dashboard

NexDial is a Vicidial-inspired Admin Panel built using Next.js, Shadcn UI, and TailwindCSS.  
It is a modern, clean, and fast dashboard for managing call centers with features like real-time monitoring, campaign setup, user management, and detailed reports.

## Features

- Dashboard: Quick stats on agents, calls, and queues  
- User Management: Add, remove, and edit agents and managers  
- Campaigns: Create and control inbound/outbound campaigns  
- Live Monitoring: Track who is on call, paused, or waiting  
- Reports: Export call volume, agent performance, and campaign data  
- Settings: Manage system configs, integrations, and audit logs  

## Tech Stack

- Next.js – React Framework  
- Shadcn UI – Prebuilt UI Components  
- TailwindCSS – Styling  
- Recharts / Chart.js – Data visualization  
- JavaScript / React  

## Project Structure

nexdial-admin/
│── pages/ # Next.js routes (dashboard, users, campaigns, etc.)
│── components/ # Navbar, Sidebar, Cards, Tables, etc.
│── styles/ # Tailwind + custom styles
│── utils/ # Helper functions
│── data/ # Mock data for testing
└── public/ # Static assets (logos, icons)

bash
Copy
Edit

## Getting Started

Clone the repository and run locally:

```bash
git clone https://github.com/harsh-narayan-nishad/NexDial-Admin-Page.git
cd nexdial-admin
npm install
npm run dev
App will be available at http://localhost:3000

For production:

bash
Copy
Edit
npm run build
npm start
Deployment
Vercel (recommended for Next.js)

Docker + AWS / Render / DigitalOcean

Supports CI/CD with GitHub Actions

Contributing
Fork the repository

Create a branch: git checkout -b feature-xyz

Commit changes: git commit -m "Added xyz"

Push the branch: git push origin feature-xyz

Open a Pull Request

