MedRoam - Tourist Medical Assistance Platform (PRD)
Project Overview
MedRoam is a comprehensive React-based frontend application designed to assist international and domestic travelers in finding verified, English-speaking healthcare providers. The platform focuses on transparent pricing, ease of search, and dedicated helpline support.

Tech Stack
Framework: React + Vite
Styling: Tailwind CSS + Material UI (MUI)
State Management: Redux Toolkit
Routing: React Router v6
Forms: Formik + Yup
HTTP Client: Axios
Notifications: React Toastify
SEO: React Helmet Async
Key Pages & Routes
Landing Page (/): Hero with city search, stats, how-it-works, featured cities, and emergency CTA.
Search Results (/search): Filterable sidebar and provider cards with skeleton loaders.
Provider Detail (/provider/:id): Full profile, pricing table, availability slots, and reviews.
Emergency Helpline (/helpline): City-specific numbers, quick connect form, and live agent status.
Login (/login): Formik-based authentication.
Register (/register): 3-step multi-page form with travel details and medical preferences.
Tourist Dashboard (/dashboard): Saved providers, appointments, and profile photo upload (drag & drop).
Admin Panel (/admin): Role-based provider management and platform stats.
Design Requirements
Primary Colors: Dark Navy (#0A1628) and Electric Teal (#00D4AA).
Typography: Plus Jakarta Sans (Headings), Inter (Body).
Aesthetic: High contrast, modern, rounded corners (xl), subtle shadows.
Urgency: Red (#EF4444) for emergency elements.
Availability: Green for "Available Now", Gray for "Unavailable".
Features & Functionality
LocalStorage/SessionStorage for auth and form progress.
Custom hooks: useAuth, useDebounce.
Mock API service with Axios interceptors and simulated delays.
Real-time "ready" structure with WebSocket placeholders.
SEO optimized with dynamic meta tags.
Fully accessible and responsive.
Atomic Components: Designed as separate, reusable components for easy Figma prototyping.
