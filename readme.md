# GigShield — Adaptive AI Insurance for India’s Gig Economy

Guidewire DEVTrails 2026 Hackathon  

Team: VibeCoders

---

## Overview

GigShield is an AI-powered parametric insurance platform designed to protect gig economy delivery workers from income loss caused by external disruptions such as extreme weather, hazardous pollution, or city-wide shutdowns.

Instead of requiring workers to file claims, the platform automatically detects disruptions and triggers payouts instantly.

The system uses AI-based risk modeling, parametric triggers, and automated claim validation to provide fast, fair, and scalable income protection for gig workers.

---

## Problem Statement

Delivery partners working for platforms like Zomato, Swiggy, and Blinkit rely on daily working hours to earn income.

However, disruptions such as:

- Heavy rain
- Severe pollution
- Extreme heat
- City strikes or shutdowns

can immediately stop deliveries and reduce their income.

### Key Challenges

- External disruptions reduce gig worker income by **20–30% monthly**
- Traditional insurance does not cover **loss of income**
- Insurance processes are **slow and complicated**
- Gig workers operate on **weekly earning cycles**

GigShield addresses this gap with a fully automated insurance solution.

---

## Our Solution

GigShield continuously monitors environmental and social signals including:

- weather conditions
- AQI levels
- government alerts
- city-wide disruptions

When a disruption occurs and workers lose earning hours, the platform automatically initiates compensation payouts.

Workers do not need to submit claims or paperwork.

---

## Adaptive Risk Subscription (ARS)

Traditional insurance uses fixed pricing.

GigShield introduces **Adaptive Risk Subscription**, where premiums adjust dynamically based on predicted disruption risk.

The AI system analyzes:

- weather forecasts
- seasonal rainfall trends
- AQI predictions
- historical disruption data
- zone-level claim patterns

### Example

| Period | Risk Level | Weekly Premium |
|------|------|------|
| January | Low | ₹19 |
| June (Monsoon) | Medium | ₹39 |
| August (Flood Risk) | High | ₹59 |

This ensures fair pricing aligned with real-world risk.

---

## Target Persona

Food delivery partners operating on platforms such as:

- Zomato
- Swiggy
- Blinkit / Zepto

### Profile

- Age: 22–35
- Weekly income: ₹6,000–₹12,000
- Device: Android smartphone
- Payment method: UPI
- Financial literacy: Basic

---

## Example Scenarios

### Heavy Rainfall

A Swiggy delivery partner in Mumbai begins a shift.

Weather API detects rainfall exceeding **80 mm/hour**.

The system detects delivery disruption and automatically initiates a payout.

The worker receives compensation directly to their UPI account.

---

### Severe Air Pollution

AQI levels exceed **500 (hazardous)** in Delhi.

GigShield detects the event and compensates insured workers operating in affected zones.

---

### City-wide Bandh

A sudden bandh occurs in Bengaluru.

Government alert feeds confirm the disruption.

GigShield automatically compensates affected workers based on historical earnings data.

---

## Application Workflow

Worker Registration
↓
AI Risk Profiling
↓
Weekly Policy Purchase
↓
Real-Time Disruption Monitoring
↓
Parametric Trigger Detection
↓
Fraud Validation
↓
Automated Claim Processing
↓
Instant Payout via UPI Simulation
↓
Dashboard Update


---

## Core Platform Features

### Fast Worker Onboarding

Workers register using:

- mobile number OTP
- delivery platform ID
- city and zone selection
- Aadhaar verification (mock)

---

### AI Risk Profiling

The system generates a risk score based on:

- weather disruption history
- flood frequency
- AQI seasonality
- worker activity consistency
- city-level disruption patterns

The score determines premium pricing.

---

### Dynamic Weekly Insurance Plans

| Plan | Weekly Premium | Coverage per Day | Max Weekly Payout |
|------|------|------|------|
| Basic | ₹29 | ₹200 | ₹600 |
| Standard | ₹49 | ₹400 | ₹1200 |
| Premium | ₹79 | ₹700 | ₹2100 |

Premiums may adjust based on predicted disruption risk.

---

## Micro-Coverage Add-ons

Workers can activate additional coverage modules.

| Add-on | Weekly Cost | Coverage |
|------|------|------|
| RainShield | ₹12 | Rain disruption |
| HeatShield | ₹8 | Extreme heat |
| AQI Shield | ₹10 | Pollution protection |

---

## Parametric Trigger System

Claims are triggered automatically when disruption thresholds are crossed.

| Trigger | Data Source | Threshold |
|------|------|------|
| Heavy Rainfall | OpenWeather API | > 64.4 mm/hour |
| Extreme Heat | Weather API | > 48°C |
| Severe AQI | AQI API | AQI > 500 |
| Flood Alert | IMD Flood Warning | Zone flooded |
| Bandh / Strike | News + Govt alerts | Verified event |

---

## Fraud Detection Engine

To prevent fraudulent claims, GigShield performs validation checks:

- GPS location verification
- worker activity validation
- duplicate claim detection
- anomaly detection using machine learning
- claim velocity monitoring

Each claim receives a **confidence score** before payout approval.

---

## Predictive Risk Engine

GigShield also predicts future disruption risks.

Workers receive proactive alerts such as:

> High rain risk predicted tomorrow. Activate RainShield coverage.

This allows workers to activate protection before disruptions occur.

---

## Worker Dashboard

Workers can view:

- active insurance coverage
- weekly premiums
- earnings protection summary
- disruption alerts
- claim history
- payout transactions

---

## Insurer Dashboard

Admin analytics dashboard provides:

- city risk heatmaps
- disruption analytics
- claim monitoring
- fraud alerts
- predictive disruption forecasts

---

## Risk Heatmap

The system visualizes disruption risk zones on city maps.

- Red: High risk
- Yellow: Moderate risk
- Green: Safe zone

This helps insurers analyze geographic risk patterns.

---

## Disruption Simulator (Demo Feature)

For demonstration purposes, the system includes a simulation tool.

Example:


Simulate Rainstorm
→ Trigger Detected
→ Claim Validated
→ Payout Executed
→ Dashboard Updated


---

## Technology Stack

### Frontend

- React.js (PWA)
- Tailwind CSS
- Redux Toolkit
- Leaflet.js (maps)
- Recharts (analytics)

---

### Backend

- Node.js
- Express.js
- PostgreSQL
- JWT Authentication
- REST APIs

---

### AI / Machine Learning

- Python
- Scikit-learn
- XGBoost / LightGBM
- FastAPI microservice

Models include:

- risk scoring model
- fraud detection model
- disruption prediction model

---

### External APIs

- OpenWeatherMap
- AQI.in / CPCB
- News API
- Government alert feeds

---

### Payments

- Razorpay Test Mode
- UPI payment simulator

---

### Infrastructure

- AWS / Render
- Docker containers
- GitHub Actions CI/CD

---

## Development Roadmap

### Phase 1 — Ideation & Foundation

- research persona
- design triggers and pricing model
- define architecture
- setup GitHub repository
- integrate weather API
- create frontend prototype

---

### Phase 2 — Core Platform

- worker onboarding
- AI risk profiling service
- insurance policy management
- disruption trigger engine
- fraud detection module
- automated claim processing
- payout simulation
- worker dashboard

---

### Phase 3 — Optimization

- advanced fraud detection
- predictive analytics dashboard
- city risk heatmap visualization
- disruption simulation tool
- performance optimization
- final demo video and pitch deck

---

## Expected Impact

GigShield provides financial protection for gig economy workers by compensating lost income caused by environmental or social disruptions.

The platform demonstrates how AI-driven parametric insurance can create scalable and accessible protection for millions of delivery partners.

---

## Submission Links

GitHub Repository  
`https://github.com/SHZunknown11/VibeCoders-GigShield-Solution`

Demo Video  
`https://youtu.be/TZ51aEOZY-A`


---

