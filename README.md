# 🏙️ Abuja Estate City AI

> AI-Powered Smart Real Estate, Construction & Property Marketplace for Abuja, Nigeria

**Built by Rabiu Hamza | Harz Technology Group | July 2026**

---

## 🚀 Live Platform

| Service | URL |
|---|---|
| Main Marketplace | https://abuja-estate-city-ai.vercel.app |
| Backend API | https://superagent-2286fb2f.base44.app/functions/abujaEstateCityAI |
| AI Estimator | https://superagent-2286fb2f.base44.app/functions/abujaEstateAI |
| Data API | https://superagent-2286fb2f.base44.app/functions/abujaEstateData |
| Inquiries | https://superagent-2286fb2f.base44.app/functions/abujaEstateInquiry |

---

## 🎯 Overview

Abuja Estate City AI is a full-stack real estate ecosystem targeting the Abuja, Nigeria property market. Phase 1 is live with 5 core modules. The platform is engineered for long-term expansion into a 20-module enterprise system.

---

## ✨ Phase 1 Features (Live)

### Real Estate Listings
- Property listings with full details (bedrooms, bathrooms, size, price)
- Listing types: For Sale, For Rent, Joint Venture
- Property types: Residential, Commercial, Land, Serviced Estate
- Location filtering (Gousa, Maitama, Wuse, Garki, Asokoro, etc.)
- Verified seller badges

### Professionals & Artisans Directory
- Categories: Architect, Civil Engineer, Structural Engineer, Quantity Surveyor
- Artisans: Mason, Plumber, Electrician, Carpenter, Painter, Welder, Tiler
- Rating system, experience years, hourly rates
- Direct contact info

### Building Materials Marketplace
- Suppliers: cement, blocks, iron rods, sand, granite, tiles, roofing
- Wholesale vs retail pricing
- Stock availability
- Lagos & Abuja supplier network

### AI Construction Cost Estimator
- Input: building type, finish level, dimensions
- Output: itemized cost breakdown in NGN
- Rates: Basic ₦200k/sqm | Standard ₦350k/sqm | Luxury ₦600k/sqm
- Phase breakdown: Foundation, Superstructure, Roofing, Finishes, MEP

### Inquiry System
- Contact form with lead tracking
- Interest categories: Buy, Rent, Sell, Invest, Build
- Backend storage via EstateInquiry entity

---

## 🗄️ Database Entities

| Entity | Fields |
|---|---|
| EstateProperty | title, type, listing_type, location, price, bedrooms, verified... |
| EstatePro | name, category, pro_type, rating, hourly_rate, verified... |
| EstateMaterial | name, supplier, price, wholesale_price, in_stock... |
| EstateInquiry | full_name, email, phone, interest, message, status |

---

## 🔭 Roadmap — 20 Module Vision

- [ ] Module 2: Smart Property Valuation AI
- [ ] Module 3: Mortgage Calculator & Bank Integration
- [ ] Module 4: Escrow & Legal Documentation System
- [ ] Module 5: 3D Property Tour (VR/AR)
- [ ] Module 6: Smart Contract (Blockchain-based titles)
- [ ] Module 7: Developer Portal & Project Tracking
- [ ] Module 8: Government Registry Integration (Abuja GIS)
- [ ] Module 9: Property Insurance Marketplace
- [ ] Module 10: Smart Home IoT Integration
- [ ] Module 11: Short-let / Airbnb Management
- [ ] Module 12: Property Management System
- [ ] Module 13: Investment Portfolio Dashboard
- [ ] Module 14: Tenant Screening & CRM
- [ ] Module 15: Construction Progress Tracker
- [ ] Module 16: Mobile App (React Native)
- [ ] Module 17: WhatsApp AI Property Assistant
- [ ] Module 18: Predictive Market Analytics
- [ ] Module 19: Commercial Real Estate Auctions
- [ ] Module 20: Pan-African Expansion

---

## 🏗️ Tech Stack

- Frontend: Next.js, React, Tailwind CSS (Vercel)
- Backend: Base44 serverless functions (Deno)
- Database: Base44 entity store (PostgreSQL)
- AI: Rule-based cost estimator + LLM integration
- Payments: Paystack (NGN), Stripe (USD)
- Map: Planned — Mapbox/Google Maps

---

## 📄 License

MIT — Built by Harz Technology Group | Abuja, Nigeria
