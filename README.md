# Full Stack Engineer Portfolio Projects

## 1. Offline-First POS System for Informal Traders

### Problem
Most small vendors operate in areas with intermittent internet but need reliable sales records.

### Solution
Build a POS system using:
- **Next.js** frontend with **IndexedDB** for offline storage
- **NestJS** backend with PostgreSQL
- **Service Workers** for caching
- **Sync engine** to reconcile offline and online data

### Goals
- Support offline product lookup, carting, and sales
- Sync when connection is restored
- Export daily reports in PDF/CSV

---

## 2. Digital Farmer’s Market (E-Commerce for Farmers)

### Problem
Smallholder farmers lack online channels to sell produce directly to consumers.

### Solution
Create a farmer-friendly online marketplace using:
- **FastAPI + PostgreSQL** for backend
- **Next.js 14 App Router** for frontend
- **M-Pesa STK push integration**
- **Mapbox** to locate farms by GPS

### Goals
- Allow farmers to list produce by location
- Enable customers to schedule delivery or pickup
- Integrate payments and SMS notifications

---

## 3. Smart Resume Matcher and Job Fit Score Engine

### Problem
Hiring managers manually scan resumes and job descriptions with bias.

### Solution
Build an AI-powered matcher using:
- **Python NLP (spaCy / GPT embeddings)** to compare resumes to job descriptions
- **React + Tailwind CSS** frontend for upload and display
- **Graph score results** by skill match

### Goals
- Automatically rank top candidates
- Offer job-specific CV feedback
- Export recruiter reports
