# IoT-SPMS MVP

This folder contains a React/Vite MVP for the Smart Parking Management System for University Campus.

## Core demo features

- Role-based login simulation: Parking User, Parking Operator, System Administrator.
- Parking availability map with Available / Nearly Full / Full states.
- University-member entry and exit flow.
- Visitor / no-ID temporary access flow.
- Sensor and gateway simulation.
- Mock billing and BKPay payment-status simulation.
- Admin pricing policy configuration.
- Audit logs and simple reports.

## Run

```bash
cd mvp
npm install
npm run dev
```

Open the local URL printed by Vite.

## MVP integration notes

External systems such as HCMUT_SSO, HCMUT_DATACORE, BKPay, IoT sensors, electronic signage, and gate controllers are simulated through mock data and mock services. This matches the MVP scope described in the software engineering report.
