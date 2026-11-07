# 🏛️ Campus Event Manager

**Campus Event Manager** is a responsive web-based portal designed for college event coordinators and faculty members to check auditorium and seminar hall availability and submit structured venue-booking requests online.

---

## 👨‍🎓 Student & Course Details

* **Name:** Tanmay Gupta
* **Roll Number:** MAINS-43925
* **Project Title:** Campus Event Manager
* **Faculty Guide:** Deepika Bhansali
* **Course:** BTech | Web Development | Course Project 2026–27
* **Project Type:** Individual Project (HTML5, CSS3, JavaScript)

---

## 📖 1. Introduction
Our college hosts numerous workshops, seminars, club activities, and cultural events throughout the academic year. Currently, checking room availability and booking campus venues requires manual coordination across multiple departments. This project brings campus venue information, availability checking, and booking requests together into a single, easy-to-use website.

---

## ⚠️ 2. Problem Statement
College clubs and faculty organizers currently rely on informal messaging apps, phone calls, and manual registers to check and book campus auditoriums or seminar halls, leading to scheduling conflicts, double bookings, and delayed approvals.

---

## 🎯 3. Project Objectives
1. Display all available campus venues (auditoriums, seminar halls, and labs) in one place with capacity, location, and equipment details.
2. Enable event coordinators to check room availability by date and time slot using an interactive lookup tool.
3. Provide a structured online booking request form to capture event details, expected attendance, and audio-visual requirements.
4. Validate all form inputs on the client side (including required fields and start/end time logic) before submission.
5. Ensure a responsive layout that works seamlessly across both mobile phones and desktop/laptop screens.

---

## 👥 4. Target Users
* **Event Coordinators / Student Leads:** Browse available campus venues, check time-slot availability, and submit equipment and venue booking requests.
* **Faculty Advisors / Administrators:** Review incoming booking details, verify club credentials, and approve or reject schedule requests.
* **General Students:** View an approved calendar of upcoming campus events and seminar schedules.

---

## ✨ 5. Main Features
1. **Home & Dashboard:** Features a welcome banner, quick statistics (total venues, active bookings), an approved event schedule, and a consistent navigation menu.
2. **Venue Catalog:** Displays available college venues (auditoriums, seminar halls, labs) as structured cards detailing seating capacity, building location, and available equipment.
3. **Interactive Venue Availability Checker:** A JavaScript-powered filter and lookup tool to check room availability by specific date and time slot.
4. **Booking Request Form:** A dedicated form allowing organizers to request a venue by specifying the event name, coordinator contact details, expected attendance, date, time slot, and required audio-visual equipment.
5. **Client-Side Form Validation:** JavaScript validation that checks required fields, verifies email/phone formats, ensures event end-times occur after start-times, and displays clear error or confirmation messages.
6. **Responsive Design:** Built with CSS media queries so pages adapt cleanly to mobile and desktop screen widths without horizontal scrolling or overlapping content.

---

## 🛠️ 6. Technologies Used
* **HTML5:** Semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) for accessible page structure and properly labelled form controls.
* **CSS3:** External stylesheet (`css/style.css`) for custom layout, typography, colour palette, card grids, and responsive media queries (no inline styles).
* **JavaScript:** External script (`js/script.js`) for interactive venue filtering, form validation, and dynamic feedback messages.
* **Git & GitHub:** Version control, code backup, and development history tracked through meaningful branch names and commit messages.

---

## 📄 7. Page / Module Description
* **Home (`index.html`):** Contains the site header, navigation bar, welcome banner, quick campus venue statistics, upcoming approved event schedule, and footer.
* **Venues (`venues.html`):** Displays all campus auditoriums, seminar halls, and labs as cards, alongside the interactive date/time availability filter and a button to proceed to booking.
* **Booking (`booking.html`):** Hosts the venue booking request form with labelled inputs for coordinator name, email, phone number, venue selection, event date, start/end times, expected attendance, and AV equipment checkboxes.

---

## 📂 8. Project Folder Structure
All files and folders strictly follow the course convention of lowercase names with hyphens and no spaces, keeping CSS, JavaScript, and images in dedicated directories:

```text
campus-event-manager/
├── index.html          # Home page, dashboard stats, and approved calendar
├── venues.html         # Venue catalog cards and availability checker
├── booking.html        # Venue and equipment booking request form
├── css/
│   └── style.css       # Organised styles, layout rules, and media queries
├── js/
│   └── script.js       # Availability filter logic and form validation
└── images/             # Logos, banners, and campus venue photos
