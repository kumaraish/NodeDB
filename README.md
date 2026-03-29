# NodeDB

A lightweight, self-contained PWA for telecom/network engineers to store and quickly access node configurations — IPs, ports, SSH/GUI credentials, SCTP addresses, point codes, SSNs, and freeform notes.

Why?
- Single HTML file — no server, no database, no dependencies
- Share by copying the file; each user's data lives in their browser's localStorage
- Export/import JSON for backup or team sharing
- Click any field to copy, admin mode to edit
- Sidebar navigation with node labels
- PWA — installable as a desktop/mobile app
- Dark theme, compact layout — built for long sessions

Usage: Open network-nodes.html in any browser. That's it.

Admin mode: Click 🔒 Admin → login with admin/admin to add, edit, or delete nodes. This is a guard against accidental edits, not a security feature.
