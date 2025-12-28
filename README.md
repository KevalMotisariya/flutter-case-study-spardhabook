# SpardhaBook – Competitive Exam Preparation App  
Flutter Case Study | Client Project

## Overview
SpardhaBook is a **production Flutter application** built for preparation of major Indian government exams such as **UPSC, MPSC, Police Bharati, Rajya Seva**, and related competitive exams.

The app consolidates **video lectures, tests, daily quizzes, study materials, analytics, job alerts, and AI assistance** into a single structured platform, helping aspirants manage complex syllabi and track progress effectively.

The application is live on the **Google Play Store** with **10,000+ downloads** and is actively used by exam aspirants across India.

> **Note:** Source code is private due to client confidentiality and NDA.  
> This repository focuses on **product ownership, architecture, and real-world problem solving**.

---

## Role & Ownership
**Sole Flutter Developer**

- End-to-end ownership of the **entire Flutter application**
- Integrated and managed **all backend APIs** (backend developed by a separate developer)
- Worked directly with a **startup client** to translate business requirements into production features
- Responsible for:
  - App architecture
  - State management
  - Performance optimization
  - Play Store–ready production builds
- Independently handled feature delivery, bug fixes, and iterative improvements

This project reflects **full individual ownership**, not team-based development.

---

## Development Timeline
**Mid 2024 – Mid 2025**

- MVP → feature-rich production release
- Continuous enhancements based on user feedback and business priorities

---

## Application Scale
- **10,000+ downloads** on Google Play Store
- Active subscription-based users
- Flexible monetization model:
  - Users purchase **individual courses** instead of paying for the entire app
  - Improves affordability and accessibility for students

---

## Core Features

### Exam-Centric Content Structure
- Exam-wise categorization (UPSC, MPSC, Police, etc.)
- Entire app experience adapts based on the selected exam category

---

### Video Learning System
- Chapter-wise video batches
- Free and paid video segregation
- Folder-based organization within chapters
- Offline video download and playback support

---

### Test & Quiz Engine
- Chapter-based tests (free & paid)
- Post-test analytics:
  - Correct
  - Incorrect
  - Skipped questions
- Test history stored for performance tracking
- **Daily Quiz module**
  - Updated daily
  - Haptic feedback (vibration) for incorrect answers

---

### Study Material & Resources
- Downloadable PDF study materials
- **In-app PDF editor**
  - Highlighting
  - Annotation
  - Markups
  - Saved locally on device
- Important external websites curated inside the app

---

### Performance & Analytics
- Dedicated **My Performance** section
- Graphs and insights generated from:
  - Test history
  - Quiz attempts
  - Exam progress
- Helps users identify weak areas clearly

---

### Additional Functional Modules
- E-Book Store (physical book ordering with delivery)
- Blog & Current Affairs section
- Job alerts based on selected exam category
- Paid courses dashboard (access to purchased content)
- YouTube live classes integration
- Bookmarking system for questions
- AI Chat Assistant powered by **Google Gemini**
- Refer-and-earn program
- Push notifications

---

### System & Security Features
- Secure authentication flow
- User profile management
- Razorpay payment gateway integration
- Cloudflare Turnstile integration for bot and abuse protection

---

## Architecture & State Management
- **State Management:** GetX
- API-driven architecture (backend-first design)
- Clear separation of:
  - UI
  - Controllers
  - API services
- Designed to support:
  - Large content volume
  - Multiple exam categories
  - Frequent data updates

---

## Key Technical Challenges & Solutions

### Dashboard Performance Optimization
**Problem**
- Initial dashboard load suffered from performance lag due to multiple simultaneous API calls

**Solution**
- Removed unused API calls
- Prioritized essential data loading
- Reordered API execution sequence
- Eliminated unnecessary loaders and refresh triggers

Result: **Noticeably faster dashboard load, even on low-end devices**

---

### Exam Calendar & Home Screen Widget
**Problem**
- Required native platform integration beyond Flutter

**Solution**
- Implemented **platform-specific code**
  - Android: Kotlin / Java
  - iOS: Swift
- Established communication between Flutter and native layers
- Built an exam date calendar with:
  - Color-based urgency indicators
  - Home screen widget support

This was one of the most technically complex parts of the app.

---

### Low-End Device Optimization
- Optimized asset loading
- Reduced memory overhead
- Carefully managed UI rebuilds
- Ensured smooth performance on budget Android devices

---

## What Makes SpardhaBook Different
- **Simplifies highly complex exam preparation**
- Exam-focused UX instead of generic learning flow
- Live performance analytics for continuous improvement
- All-in-one digital toolkit:
  - Videos
  - Tests
  - PDFs
  - Current affairs
  - Analytics
- Effectively replaces **hundreds of pages of physical books** with a structured mobile-first experience
  
---

## Live Application
Google Play Store:  
http://play.google.com/store/apps/details?id=com.spardhabook.edtechllp

---

## Final Note
This project demonstrates the ability to:

- Independently own a large Flutter codebase
- Deliver complex, domain-specific products
- Optimize for real users on real devices
- Build scalable, monetized mobile applications for the Indian market

The focus of this case study is **execution, ownership, and product thinking** — not demo-level code.
