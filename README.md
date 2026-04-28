# 🚗 Triphood

> **The Road Trip Lifestyle Platform for Thailand & Southeast Asia**

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=flat&logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=flat&logo=dart)](https://dart.dev)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-lightgrey?style=flat)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat)](#license)
[![Status](https://img.shields.io/badge/Status-In%20Development-green?style=flat)]()

---

Triphood is where road trippers and car enthusiasts belong. Rent a vehicle, shop road trip gear, join car clubs, host events, sell e-tickets, and plan your next journey with an AI-powered route planner — all in one Flutter app built for Thailand and Southeast Asia.

---

## 📖 Table of Contents

- [About Triphood](#about-triphood)
- [Platform Pillars](#platform-pillars)
- [Features Built](#features-built)
- [AI Trip Planner](#ai-trip-planner)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Looking for Contributors](#looking-for-contributors)
- [Roadmap](#roadmap)
- [License](#license)
- [Contact](#contact)

---

## About Triphood

**Triphood** combines *trip* and *hood* — neighbourhood, brotherhood, the people you belong with on the road.

Most road trip apps solve one problem. Triphood solves the whole journey. Whether you own your car or need to rent one, whether you are planning a solo drive or hosting a car meet for 500 people — Triphood is your complete companion from the moment you start planning to the moment you arrive.

> *"Triphood is not just where you book the car. It is where the road trip community lives."*

---

## Platform Pillars

Triphood is built on four independent but deeply connected pillars:

### 🚗 Mobility
Thailand's most complete vehicle booking layer. Every vertical shares a single checkout, in-app wallet, and review system.

| Vertical | Description |
|---|---|
| Car Rental | Short-term self-drive hire with transparent fleet pricing |
| Car & Hotel | Bundled vehicle + accommodation — one checkout, one bill |
| Long Rental | Monthly subscription rental with digital contracts and district-aware pricing |
| Airport Transfer | To/from airport with driver — flight-aware pickup with extras marketplace |
| Limousine | Premium chauffeured rides |
| Car & Driver | Self-drive + personal driver with add-ons (child seats, GPS, luggage handling) |
| Car & Event | Vehicle booking linked to event attendance |
| Sport & Performance | Supercar and track-day rental — Thailand's first structured marketplace |
| EV Car | Electric vehicle rental with charging-aware routing |
| Road Trip Package | Multi-day guided route + car + accommodation as one itinerary-first booking |

---

### 🛒 Marketplace

> **You do NOT need to rent a car to use Triphood.**

The majority of road trippers own their vehicle. Triphood captures their spend through a road-trip-native marketplace that surfaces products relevant to their specific route and destination.

**What the marketplace sells and rents:**
- Road trip gear — rooftop tents, coolers, portable power stations, camping kits
- Gadgets & tech — dash cams, GPS units, action cameras, CB radios, inverters
- Food & dining — route-stop restaurant vouchers, picnic kits, local food boxes
- E-vouchers — fuel discounts, toll credits, hotel upgrades, spa passes
- Safety & emergency — jump starters, first aid kits, tow ropes, tyre inflation kits
- Airport products — SIM cards, travel pillows, luggage, forex, duty-free
- Experience packages — guided hikes, boat tours, cooking classes tied to route stops
- Insurance — per-trip and per-day travel and vehicle cover
- Fuel cards — pre-paid fuel discounts at partner stations nationwide
- Vehicle accessories — car wraps, seat covers, LED kits, performance parts

---

### 🤝 Community

The social layer that creates retention no competitor can replicate quickly.

- **Route & Trip Sharing** — post routes with photos, gear lists, tips, and GPS tracks
- **Car Clubs & Groups** — official club pages, member directories, and group trip planning
- **Community Marketplace** — members sell or rent personal gear and vehicles peer-to-peer
- **Road Trip Challenges** — gamified route completion badges (e.g. "Completed the Northern Loop")
- **Expert Content** — member-written guides, mechanic tips, and destination deep-dives
- **Triphood Forums** — category boards: 4WD, EV, motorcycle, family trips, overlanding
- **Partner Spotlights** — local guesthouses, mechanics, and eateries featured along routes

---

### 🎪 Events

Triphood's most unique and defensible layer. No platform in Thailand combines venue discovery, event hosting, e-ticket issuance, and an in-event product storefront into a single flow.

**Complete event flow — end to end:**

| Step | What the host does |
|---|---|
| 1. Discover a Venue | Browse circuits, car parks, showrooms, outdoor spaces, and private land |
| 2. Book the Venue | Secure booking with escrow payment and digital venue agreement |
| 3. Create the Event | Build a branded event page with route map, schedule, and banner |
| 4. Set Ticket Tiers | General, VIP, Paddock, Spectator, Kids — each with its own price and capacity |
| 5. Open the Host Store | List branded merch, food vouchers, photography, car care, and digital downloads |
| 6. Manage Attendees | View registrations, verify vehicles, broadcast announcements |
| 7. Run the Event | QR code gate check-in, live leaderboards, real-time updates |
| 8. Post-Event | Media hub, automated payout within 48 hours, audience analytics |

**Hosts keep 88–92% of ticket revenue** — the most competitive rate of any ticketing platform in Thailand.

**Venue types supported:** motor circuits, mall car parks and plazas, showrooms and dealerships, outdoor and nature spaces, hotels and resorts, petrol stations and rest stops, event halls and warehouses, private estates.

---

## Features Built

The following features are built and running in the current codebase:

- ✅ **10+ transport verticals** — full booking flow for every mobility service
- ✅ **Multi-gateway payments** — PromptPay QR, credit/debit card, bank transfer, crypto, in-app wallet
- ✅ **Airport transfer** — flight-aware pickup time with real-time sync and add-on extras marketplace
- ✅ **Long rental** — district-aware pricing engine with digital contract generation
- ✅ **Event hosting flow** — event creation, tiered ticket pricing, attendee management
- ✅ **QR e-ticket generation** — unique QR code per attendee, issued instantly on purchase
- ✅ **Mobile check-in scanner** — built-in QR gate scanner in the host dashboard
- ✅ **In-event host store** — product listing, checkout, order management, and automated payout
- ✅ **Vendor portal** — fleet management, booking intake, earnings dashboard
- ✅ **Customer dashboard** — manage all active bookings across every vertical
- ✅ **Review system** — verified booking-triggered reviews with rating display
- ✅ **Add-on marketplace** — airport products (buy) and equipment (rent) with edit and remove flow
- ✅ **Multi-luggage types** — checked, cabin, and personal bag breakdown per passenger
- ✅ **Like and review interactions** — real-time like toggle with count sync and review bottom sheet

---

## AI Trip Planner

Triphood includes an AI-powered road trip planner that recommends personalised routes based on the user's destination, preferences, travel history, and community data.

**How it works:**
- User inputs their destination or selects from the Route Library
- The AI analyses the route and surfaces relevant recommendations: fuel stops, scenic viewpoints, local food, gear suited to the terrain, and nearby community events
- Recommendations are personalised based on vehicle type, group size, trip duration, and past trips
- Route-aware marketplace: products change dynamically as the route is refined — a northern mountain loop surfaces camping gear; a coastal drive surfaces snorkelling packages and beach restaurant vouchers
- Community layer: routes include ratings, tips, and photos from Triphood members who have driven the same road

**Planned AI features:**
- [ ] Conversational trip planner — describe your trip in natural language, get a full itinerary
- [ ] Real-time traffic and road condition alerts along the planned route
- [ ] Dynamic rerouting based on weather, road closures, and event locations
- [ ] Personalised event recommendations based on route and interests
- [ ] Predictive gear suggestions based on season, terrain, and trip length

---

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile framework | Flutter 3.x (iOS + Android) |
| Language | Dart 3.x |
| State management | Provider |
| UI | Custom design system — navy/blue/cyan/green palette, gradient cards |
| Payments | Multi-gateway: PromptPay QR, credit card, bank transfer, crypto, in-app wallet |
| Maps & routing | Google Maps SDK + route intelligence layer |
| Backend | REST API |
| Authentication | JWT-based auth with user account model |
| Storage | Local state + remote API sync |

---

## Project Structure

```
lib/
├── models/
│   ├── car_airtransfer.dart        # Car and airport transfer models
│   ├── thailand_airports.dart      # Airport data model
│   ├── user_account.dart           # User account model
│   ├── review.dart                 # Review model
│   ├── airtransfer_extras.dart     # Airport and province extra items
│   └── mock_products_airports.dart # Mock product data for airports
│
├── screens/
│   ├── air_transfer/
│   │   ├── airtransfer_carlist_from_airport_screen.dart
│   │   └── air_transfer_car_detail_to_airport_screen.dart
│   ├── car_rental/
│   ├── long_rental/
│   ├── events/
│   ├── marketplace/
│   └── community/
│
├── widgets/
│   └── car_stats_row.dart          # Shared stats row widget
│
└── main.dart
```

---

## Getting Started

### Prerequisites

- Flutter SDK 3.x
- Dart SDK 3.x
- Android Studio or Xcode
- A device or emulator running Android 6.0+ or iOS 13+

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/triphood-flutter.git

# Navigate into the project
cd triphood-flutter

# Install dependencies
flutter pub get

# Run on a connected device or emulator
flutter run
```

### Environment setup

Create a `.env` file in the root directory (not committed to version control):

```
API_BASE_URL=your_api_url
GOOGLE_MAPS_KEY=your_maps_key
PAYMENT_GATEWAY_KEY=your_payment_key
```

---

## Looking for Contributors

Triphood is a real product with a real architecture already in place — not a wireframe looking for someone to build from scratch.

**What I am looking for help with:**
- UI/UX polish — bring the design system to its full potential
- AI trip planner — route recommendation engine and conversational planner
- Backend integration — REST API connections for new features
- Performance optimisation — smooth 60fps on mid-range Android devices
- Community features — clubs, route sharing, forums, challenges
- Events platform — completing the full host and attendee flow

**What I am offering:**
- Equity stake for a technical co-founder
- Contract/retainer for specific features
- Revenue share for ongoing contributors

**To apply:**
- Open an Issue describing what you can contribute
- Or email directly — contact details below

---

## Roadmap

### Phase 1 — Bangkok Launch (Q4 2025)
- [ ] Public app launch — Bangkok
- [ ] 20 anchor venues onboarded
- [ ] 10 car club partnerships live
- [ ] Marketplace with 40+ vendors
- [ ] First 5 Triphood-powered events
- [ ] AI trip planner (v1) — destination-based route recommendations

### Phase 2 — National Rollout (Q1–Q2 2026)
- [ ] Expand to Phuket, Chiang Mai, Pattaya
- [ ] Route Library — 50 curated routes
- [ ] Triphood Wallet loyalty — Hood Points across all pillars
- [ ] AI trip planner (v2) — conversational and personalised
- [ ] OEM partnerships (BYD, MG, Isuzu Thailand)
- [ ] Triphood Road Trip Rally #1 — flagship national event

### Phase 3 — SEA Expansion (2026+)
- [ ] Malaysia, Vietnam, Indonesia
- [ ] Localised payment rails per market
- [ ] Triphood Expo — annual automotive lifestyle expo
- [ ] Series A fundraise

---

## License

Copyright © 2025 Triphood Co., Ltd. All rights reserved.

This repository and its contents are proprietary. No part of this codebase may be copied, modified, distributed, or used for commercial purposes without explicit written permission from the copyright holder.

Contributors to this repository agree that all contributions become the intellectual property of Triphood Co., Ltd. under a signed Contributor License Agreement (CLA).

---

## Contact

** Triphood **
Bangkok, Thailand

- 📧 Email: chutichotpondach@gmail.com.`
- 🌐 Website: `triphood.co` *(coming soon)*

---

<div align="center">

**Built in Bangkok. Built for the road.**

*🚗 Rent · 🛒 Shop · 🤝 Connect · 🎪 Celebrate*

</div>
