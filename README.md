# Solomates ✈️

Solomates is a no-code web app for solo travelers to find compatible travel buddies and form small micro-groups based on destination, dates, vibe, budget, and interests.

## 🔗 Live App
- Published App: https://solomates.lovable.app/
- Preview (if needed): PASTE_YOUR_PREVIEW_LINK

## 🎥 Loom Walkthrough
- Loom Video: (https://www.loom.com/share/121afdb7462b4a7ebd399d5a956e6336)

## ✅ Assignment Checklist
- Landing page describing idea ✅
- Signup / Login / Forgot Password ✅
- CRUD in action (Trips) ✅  
  - Create trip  
  - Read trips list  
  - Update trip  
  - Delete trip  
- Discover section with Trips + People tabs ✅
- Compatibility score visible ✅
- Groups visible & joinable ✅
- Supabase database connected ✅

## 🧠 Idea
Solo travel is growing fast, but travelers often struggle with safety and loneliness.
Solomates solves this by matching travelers who overlap on:
- Destination  
- Dates  
- Travel vibe/style  
- Budget range  
- Interests  

Users can then form micro-groups (3–5 people) for safer and more fun travel.

## 🛠 Tech Stack
- Frontend / Vibe Coding Tool: **Lovable**
- Database + Auth: **Supabase**
- Version control / documentation: **GitHub**
- Presentation: **Loom**

## 🗃 Database Schema (Supabase)
Tables used:
1. `users` – traveler profiles
2. `trips` – trips CRUD
3. `groups` – one group per trip
4. `group_members` – membership join/leave

## 🚀 How it works (User flow)
1. User signs up / logs in  
2. Creates traveler profile  
3. Creates a trip
Visits Discover:
   - Trips tab → browse trips + compatibility  
   - People tab → browse travelers + compatibility  
5. Joins a group linked to a trip  
6. Views groups in My Groups tab

## 📌 Future Scope
- In-group chat
- Safety verification badges
- Location-based live recommendations
- Smart itinerary builder
