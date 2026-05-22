# BnB-helper

An AI-assisted property management platform designed for Airbnb hosts and short-term rental operators to streamline property operations, automate guest communication, and simplify day-to-day management.

BnB-helper connects with major booking platforms such as Airbnb, VRBO, and Booking.com to centralize reservations, guest information, notifications, cleaning coordination, and operational workflows into a single dashboard.

---

# Overview

Managing short-term rental properties across multiple platforms can quickly become overwhelming.  
BnB-helper aims to reduce repetitive admin work by automating operational tasks and improving communication between hosts, guests, and service providers.

This project focuses on practical automation for:

- Guest communication
- Reservation management
- Property operations
- Cleaner scheduling
- Check-in/check-out workflows
- Damage claims and incident tracking
- AI-assisted messaging and notifications

---

# Core Features

## Property Management

- Multi-property dashboard
- Property status overview
- Reservation calendar management
- Occupancy tracking
- Guest history records
- Property notes and operational logs

---

## OTA Platform Integration

Connect and synchronize data from external booking platforms:

- Airbnb
- VRBO
- Booking.com
- Expedia (planned)

### Supported Operations

- Reservation synchronization
- Guest information import
- Booking status updates
- Calendar sync
- Availability management

> The project is designed to use official APIs where available and compliant data synchronization methods for supported platforms.

---

## Guest Information Management

Automatically organize and manage:

- Guest names
- Stay dates
- Occupancy details
- Contact information
- Arrival/departure schedules
- Special requests

---

## Digital Check-in Guide Editor

Create and manage customizable guest guides:

- Wi-Fi instructions
- Parking information
- Self check-in instructions
- Smart lock codes
- House rules
- Emergency contacts
- Local recommendations

### Planned Features

- Rich text editor
- Template system
- Multi-language support
- PDF export
- Mobile-friendly guide pages

---

## Automated Guest Messaging

Automatically send personalized notifications to guests at different stages of their stay.

### Check-in Notifications

Examples:

- Arrival reminders
- Door access instructions
- Parking details
- House rules
- Wi-Fi credentials

### During Stay

- Mid-stay check-ins
- Issue reporting reminders
- Upsell opportunities

### Check-out Notifications

Examples:

- Checkout reminders
- Cleaning instructions
- Key return instructions
- Review requests

---

## SMS Notification System

Integrated messaging automation for:

- Guest reminders
- Cleaner notifications
- Maintenance alerts
- Emergency updates

### Planned Providers

- Twilio
- AWS SNS
- MessageBird

---

## Cleaner Scheduling & Operations

Coordinate cleaning workflows automatically.

### Features

- Auto-assigned cleaning tasks
- Cleaner notification system
- Cleaning status tracking
- Turnover scheduling
- Cleaner notes and reports
- Photo upload support (planned)

---

## Damage Claims & Incident Management

Track property damage and operational incidents.

### Features

- Incident reporting
- Guest damage records
- Evidence upload
- Claim workflow management
- Internal notes
- Resolution tracking

---

# AI Features

BnB-helper explores the use of AI coding tools and AI-assisted workflows for operational automation.

### Planned AI Capabilities

- AI-generated guest replies
- Smart message templates
- Sentiment analysis
- Automated support suggestions
- FAQ auto-response
- Multi-language translation assistance

---

# Tech Stack

## Frontend

- React
- Next.js
- Tailwind CSS

## Backend

- Node.js
- Express

## Database

- PostgreSQL

## Integrations

- Airbnb API
- Booking.com API
- VRBO Integration
- Twilio SMS API

## AI Tools

- OpenAI API
- Codex-assisted development

---

# Project Goals

This project was started as a practical exploration of:

- AI-assisted software development
- Short-term rental operational automation
- Full-stack web application architecture
- Real-world SaaS workflow design

The long-term vision is to build a modern operational platform that helps hosts save time, reduce manual work, and improve guest experience.

---

# Roadmap

## Phase 1

- [ ] User authentication
- [ ] Property dashboard
- [ ] Reservation management
- [ ] Basic messaging system

## Phase 2

- [ ] Airbnb integration
- [ ] Cleaner scheduling
- [ ] SMS automation
- [ ] Guest guide editor

## Phase 3

- [ ] AI-assisted guest replies
- [ ] Multi-platform synchronization
- [ ] Damage claim workflows
- [ ] Mobile optimization

## Future Ideas

- [ ] Revenue analytics
- [ ] Dynamic pricing tools
- [ ] AI voice assistant
- [ ] Automated maintenance workflows
- [ ] Team collaboration system

---

# Installation

```bash
git clone https://github.com/your-username/BnB-helper.git

cd BnB-helper

npm install

npm run dev
