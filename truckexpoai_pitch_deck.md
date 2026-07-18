# TruckExpoAI – AI-Native Co-Pilot for European Commercial Trucking

*Next-generation dual-AI in-cab voice assistant and safe-routing navigator.*

---

## Slide 1: The Problem
### Commercial driving is complex, dangerous, and heavily penalized.
*   **Regulatory Penalties:** Under EU Regulation 561/2006 (HOS), fines for daily driving time violations reach up to €5,000.
*   **Unsafe Routing:** Consumer apps (Google Maps, Waze) do not support truck dimensions, routing heavy trucks under low-clearance bridges or weight-restricted zones, leading to accidents and delays.
*   **Driver Distraction:** Interacting with complex navigation screens and tachograph timers while driving is a major safety hazard.

---

## Slide 2: The Solution – TruckExpoAI
### A hands-free, safe-routing companion built for truck cabins.
*   **Dual-AI Voice Assistant:** Integrates Gemini 2.0 Flash for natural voice conversation and instant HOS checks, and GPT-4o for converting speech intents to active map actions.
*   **Real-time Tacho Sync:** Connects to the vehicle's digital tachograph via Bluetooth (BLE) to track driving/resting hours automatically.
*   **Truck-Safe Navigation:** Embedded Mapbox & TomTom routing engine configured with HGV (Heavy Goods Vehicle) profiles (height, weight, length, axle count, ADR hazmat class).

---

## Slide 3: How It Works (Technology Stack)
### Seamless integration from hardware to LLM orchestration.
*   **Frontend:** Cross-platform React Native + TypeScript app with `@rnmapbox/maps` and native Bluetooth (BLE) bridges.
*   **Backend:** High-performance Flask API proxied with SQLite and Redis for caching.
*   **Dual-AI Orchestration:**
    *   **Gemini 2.0 Flash:** Serves as the primary driver companion (very low latency, Bulgarian/English support, HOS queries).
    *   **GPT-4o:** Functions as a spatial-to-JSON compiler, parsing user navigation commands into structured MapActions (e.g., adding waypoints, finding parking spots at 82% of route capacity).

---

## Slide 4: Market Opportunity
### A massive, underserved sector.
*   **European Road Freight:** A €350 Billion industry responsible for moving over 70% of land cargo in Europe.
*   **Addressable Users:** Over 6 Million commercial truck drivers operating in the EU.
*   **High Willingness to Pay:** Fleet operators and independent owner-operators are highly motivated to avoid costly HOS fines, route deviations, and fuel wastage.

---

## Slide 5: Business Model
*   **B2C (SaaS):** Monthly recurring subscription model for individual truck drivers (premium voice/HOS planning and navigation).
*   **B2B (Enterprise):** API integration and custom dashboard licenses for fleet management companies (FMCs) to track real-time driver compliance and truck telemetry.

---

## Slide 6: The Team
*   **Miroslav (CEO & Founder):** Experienced entrepreneur with deep domain expertise in transport logistics and modern AI applications.
*   **AI-Native Tech Stack:** Built with modern DevOps, clean codebase architecture, and robust state management.

---

## Slide 7: Contact Info
*   **Email:** `ceo@truckexpoai.com`
*   **Website:** `https://truckexpoai.com`
