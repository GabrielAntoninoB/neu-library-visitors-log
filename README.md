# NEU Library Visitor Log

The NEU Library Visitor Log is a assign task to do for midterm project. It replaces paper-based logbooks with a real-time digital system that records, tracks, and reports visitor activity, from time of entry to time of departure.


The system is publicly hosted on Firebase Hosting and uses Firebase Firestore as its live database, ensuring all data is persisted securely in the cloud and accessible by authorised administrators in real time.


##Purpose
- Automate visitor check-in and check-out through a self-service kiosk-style web form.
- Eliminate manual timekeeping by recording time-in and time-out automatically on successive logins.
- Provide administrators with real-time analytics on visitor counts, types, purposes, and duration.
- Generate a persistent, searchable audit trail of every library visit.

##Language and Tools Use
- Frontend (HTML5, CSS3, JavaScript)
- Database (Firebase Cloud Firestore)
- Authentication (Firebase Auth)
- Hosting (Firebase hosting)

## Project Structure
- `index.html` — Landing page
- `StudentLogin.html` — Student login page
- `AdminLogin.html` — Admin login page
- `VisitorsPurpose.html` — Visitor log form
- `AdminDashboard.html` — Admin statistics and log viewer

## Live Application
https://neu-library-visitors-log.web.app
