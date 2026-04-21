# Common Ground

Common Ground is a web platform that centralizes trusted legal, healthcare, and community resources while enabling community members and organizations to share events and support opportunities.

## Overview

Common Ground addresses the challenge of fragmented support systems by organizing critical information into a structured, accessible interface. In addition to resource discovery, the platform integrates a community event system to highlight local programs, workshops, and services.

## Features

- Structured resource categories (legal, healthcare, housing, community, etc.)
- Clean, readable resource listings with external links
- Interactive filtering system for browsing resources
- Community event calendar with real-time updates
- Event submission system with approval workflow
- Automated pipeline:
  - Google Form → Google Sheets → Approval → Calendar → Website
- Responsive multi-page layout (Home, About, Resources, Community)

## System Workflow

- Users submit events through a form
- Submissions are stored and reviewed in Google Sheets
- Approved events are automatically added to Google Calendar via Apps Script
- Events are displayed dynamically on the website

## Tech Stack

- HTML
- CSS
- JavaScript (client-side rendering + API integration)
- Google Forms (data collection)
- Google Sheets (data storage and moderation)
- Google Apps Script (automation)
- Google Calendar API (event display)

## Author

TJ Blechman
