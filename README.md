# Roadsathi
RoadSathi – An integrated highway rescue platform connecting stranded travellers, verified mechanics, spare-parts suppliers and family members through a unified emergency workflow.
# 🚗 RoadSathi

### Sustainable Highway Rescue Network

RoadSathi is an integrated highway rescue platform that connects stranded travellers, verified mechanics, spare-parts suppliers and family members through one emergency workflow.

It is designed to provide fast, reliable and safer roadside assistance, especially during highway breakdowns, night-time emergencies and low-connectivity situations.

---

## 🏆 Smart India Hackathon 2026

**Problem Statement ID:** SIH26205  
**Problem Statement:** Student Innovation – Submit your ideas to address the growing pressures on the city’s resources, transport networks, and logistic infrastructure.  
**Theme:** Transportation & Logistics  
**Category:** Software  
**Team ID:** 169778  
**Team Name:** ZERODAY CREW

---

# 📌 Problem Statement

Highway vehicle breakdowns can quickly become safety emergencies, especially at night or in isolated areas.

Travellers currently face several challenges:

- Finding reliable roadside assistance is difficult.
- Travellers depend on scattered phone numbers and local contacts.
- Uncertain pricing can result in unexpected repair costs.
- Nearby garages remain disconnected from stranded travellers.
- Poor network connectivity can make internet-dependent assistance unavailable.
- Existing roadside assistance often focuses only on the vehicle while leaving the safety and travel needs of the family unresolved.

According to the data presented in our SIH presentation, 1,68,491 road deaths and 4,61,312 accidents were recorded in 2022, with approximately 19 deaths every hour.

The presentation also highlights that 36.2% of deaths occurred on National Highways, which account for only around 2.2% of road length.

---

# 💡 Proposed Solution

RoadSathi provides a coordinated highway rescue system that connects:

- Stranded Travellers
- Verified Mechanics
- Spare-Parts Suppliers
- Family Members
- Local Garages

### Key Features

### 🚨 One-Tap SOS

Travellers can raise an emergency request through the mobile application with their location and vehicle details.

### 📱 SMS Fallback

If internet connectivity is unavailable, a text message containing the traveller's location can create the rescue request and receive an ETA.

### 🔧 AI Fault Triage

RoadSathi uses AI-based fault triage to predict possible vehicle problems and identify the required tools or parts.

### 👨‍🔧 Smart Mechanic Matching

The platform finds nearby verified mechanics based on location, availability and service requirements.

### 🧩 Parts-Aware Routing

The system can identify nearby spare-parts shops and help the mechanic obtain missing parts while travelling to the stranded vehicle.

### 💰 Price Locking

The estimated service price is fixed before the mechanic leaves, reducing unexpected repair costs.

### 🔐 Mechanic Verification

Mechanics are verified using KYC and an arrival-code mechanism.

### 👨‍👩‍👧 Guardian Link

Family members can receive alerts and monitor the travel/rescue journey remotely.

### 🚌 Safe Journey Home

If the vehicle cannot be repaired immediately, RoadSathi can help arrange a verified cab, bus or train while keeping the vehicle secure overnight.

---

# ⚙️ Technical Approach

RoadSathi follows a layered architecture consisting of:

1. SOS Request & User Input
2. User Interface
3. Core Platform – AI & Matching
4. Services & Navigation
5. Communication & Safety
6. Backend & Data Layer
7. Offline / Fallback Route

---

## 🏗️ System Workflow

```text
Traveller
    │
    ▼
SOS Request
    │
    ├── GPS Location
    ├── Vehicle Details
    └── Problem Description
    │
    ▼
User Interface
    │
    ├── Mobile App
    └── Web Portal
    │
    ▼
Core Platform
    │
    ├── AI Fault Triage
    ├── Mechanic Matching
    └── Parts-Aware Routing
    │
    ▼
Services & Navigation
    │
    ├── Maps & GPS
    ├── Route Optimisation
    └── ETA & Distance
    │
    ▼
Communication & Safety
    │
    ├── Guardian Link
    ├── Mechanic Verification
    ├── Price Locking
    └── SMS / In-App Alerts
    │
    ▼
Verified Highway Rescue
