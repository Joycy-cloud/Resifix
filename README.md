# ResiFix — Smart Residential Management System

ResiFix is a responsive front-end prototype for reporting and tracking maintenance issues in housing societies.

## Prototype features
- Resident issue reporting with category, location, description, target date, and optional photo selection
- Administrator demo view for searching issues and changing statuses
- English, Marathi, and Hindi language selector
- Voice complaint assistant using browser speech recognition and speech synthesis where supported
- Review-and-confirm step before a voice complaint is submitted
- Sample issue data for demonstration

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Allow microphone access if you want to test the voice assistant. Speech recognition support varies by browser and device.

## Important prototype limitations
This is a browser-only demo. It is not yet connected to AWS or a production backend. Sample complaints and demo status changes are not shared across different users. Real authentication, secure role-based access, durable complaint storage, secure photo uploads, and email/SMS notifications must be implemented before real residents use the system. The demo login or UI controls must not be treated as secure authentication.

## Suggested next deployment step
Connect this repository to AWS Amplify Hosting for static website hosting and GitHub-based continuous deployment. Add a secure backend separately before using real resident data.
