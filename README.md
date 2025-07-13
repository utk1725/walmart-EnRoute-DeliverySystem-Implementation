# 🚚 Walmart EnRoute Delivery System (Hackathon Project)

> A scalable, production-level delivery enhancement system that enables users to pick up orders from smart chokepoints instead of fixed home delivery — reducing last-mile delivery costs and boosting logistics efficiency.

🎥 Demo Video:
[https://drive.google.com/file/d/1C8tIa\_arzqdpKl5MaQfl\_EaM5S7TG\_CK/view?usp=sharing](https://drive.google.com/file/d/1C8tIa_arzqdpKl5MaQfl_EaM5S7TG_CK/view?usp=sharing)

---

## 🧠 Project Idea

Walmart delivers millions of orders daily — but faces major challenges in the last-mile phase:

* Failed deliveries when users are unavailable.
* Traffic congestion around delivery zones.
* High costs due to low route optimization.

To solve this, we built an “EnRoute Delivery” system — allowing users to pick up their orders from dynamic chokepoints (e.g., metro stations, public kiosks, parking hubs) en route to their destination.

---

## 🚀 Features

✅ Address → Coordinates (geocoding)
✅ Zone detection via coordinates
✅ Real-time Chokepoint discovery
✅ Interactive Leaflet Map
✅ User selection of preferred chokepoint
✅ Smart Time Slot assignment (load-balanced)
✅ Order placement and scheduling
✅ Backend + Database integration with MongoDB
✅ Fully mobile-friendly UI using Tailwind + React

---

## 🏗️ Tech Stack

* 🟦 React + Tailwind CSS (frontend)
* 🟨 Node.js + Express (backend)
* 🍃 MongoDB + Mongoose (database)
* 🌍 Leaflet + OpenStreetMap (map & geocoding)
* ⚙️ TypeScript across backend + frontend
* 📦 Vite + TSX for dev tooling
* 🧪 React Query + ShadCN UI

---

## 📁 Folder Structure

```
WalmartClone/
├── server/                 ← Express backend
│   ├── models/             ← Mongoose models
│   ├── routes/             ← API routes
│   ├── seed/               ← Seeder scripts
│   ├── utils/              ← Helper functions
│   ├── index.ts            ← Main entry point
│   └── ...
├── src/                    ← React frontend
│   ├── pages/              ← UI pages (Home, EnrouteMap, Delivery)
│   ├── components/         ← Reusable UI components
│   ├── utils/              ← Client-side helpers (geocoding, etc.)
│   └── ...
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Environment Variables (.env)

Create a file named .env in the root with:

```
MONGO_URI=mongodb://localhost:27017/walmart-clone
```

> You can change the DB name or URI as needed.

---

## 🧪 How to Run the Project Locally

Step-by-step instructions:

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/WalmartClone.git
cd WalmartClone
```

2. Install all dependencies:

```bash
npm install
```

3. Seed the chokepoints in MongoDB:

```bash
npx tsx server/seed/seedChokePoints.ts
```

4. Run the dev server:

```bash
npm run dev
```

This will:

* Start the Express + Vite dev server on [http://localhost:5000](http://localhost:5000)
* Serve both the frontend and backend on a single port

5. Visit [http://localhost:5000](http://localhost:5000) to try out:

* Home page
* EnRoute address search
* Chokepoint selection
* Slot assignment
* Order summary

---

## 📈 Impact

✔ Reduces last-mile delivery cost by ₹10–₹15/order
✔ Routes are optimized via chokepoints, avoiding failed deliveries
✔ 5% conversion to EnRoute delivery = ₹15+ Cr annual savings
✔ Users get flexibility and faster pickup with minimal wait time

---

## 🙌 Authors

Built by @utk1725 and team during Sparkathon 2025


linkedln : https://www.linkedin.com/in/utkarshsingh1702


---
