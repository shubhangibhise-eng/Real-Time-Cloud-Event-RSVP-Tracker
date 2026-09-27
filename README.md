# Real-Time Cloud-Based Event Planning & RSVP Tracker

> Cloud computing course project | Python FastAPI · Real-Time Updates · JWT Auth · Role-Based Access · Capacity Management · Analytics

---

## Live Demo

Open `EventFlow — Real-Time Cloud RSVP Tracker.html` in your browser.

**Demo Accounts (password for all: `pass123`)**

| Name | Email | Role |
|---|---|---|
| Alice Chen | alice@eventflow.io | Organizer |
| Bob Sharma | bob@example.com | Attendee |
| Carol Nair | carol@example.com | Attendee |
| Eve Rodrigues | eve@example.com | Organizer |

---

## Cloud Computing Concepts Demonstrated

| Concept | Where It Appears |
|---|---|
| Cloud Authentication | JWT Bearer tokens, bcrypt password hashing |
| Real-Time Database | Live RSVP counters update without page refresh |
| REST APIs | Full CRUD — events, RSVPs, announcements |
| Role-Based Access Control | ORGANIZER vs ATTENDEE permissions |
| Atomic Transactions | Race-condition-safe capacity enforcement |
| Serverless-Ready | Stateless handlers, environment variable config |
| Cloud Deployment | Vercel (frontend) + Google Cloud Run (backend) |
| In-App Notifications | Bell icon with unread badge |
| Event-Driven Architecture | RSVP triggers notification and dashboard update |
| Scalability | Architecture supports load balancing and autoscaling |

---

## Features

### Organizer
- Create, edit, cancel events
- Set capacity, date, venue, online link
- Live dashboard — RSVP counts update in real time
- Post announcements to all RSVPed attendees
- View analytics: response rate, capacity utilization
- See full attendee list

### Attendee
- Browse and search all events
- RSVP: Going / Maybe / Not Going
- Update or cancel RSVP anytime
- Join waitlist when event is full
- Receive in-app notifications
- View personal RSVP history

### System
- Capacity enforcement — auto-marks event FULL
- FIFO waitlist with automatic promotion
- Race-condition-safe concurrent RSVP (atomic transaction)
- Registration deadline enforcement
- Event cancellation notifies all attendees

---

## Architecture
