# TMS Trainee UI React Prototype

A front-end-only React/Vite prototype for the **Trainee Management System (TMS)** from the **trainee perspective**.

## Included screens

- Dashboard (used as the primary landing screen instead of Onboarding)
- My Profile
- Attendance
- Leave Management
  - Industrial: Sick Leave
  - PROTÉGÉ: Annual Leave, Compassionate - Death, Compassionate - Serious Illness, Examination Leave, Leave Without Pay, Paternity Leave, Prolonged, Prolonged Illness Leave, Sick Leave - Hospitalization, Sick Leave - Non-Hospitalization, Special Leave - Marriage Leave, Unrecorded Leave
  - PROTÉGÉ balances: Annual Leave Balance, Expire Annual Leave Balance, Unrecorded Leave Balance
  - Remarks and file attachment fields
- Allowance
- Claim Management
  - Industrial: Mileage, Sustenance, Lodging, Laundry
  - PROTÉGÉ: Travel Expenses, Mileage, Sustenance, Hotel Accommodation, Lodging
  - Mileage form sections: personal information, vehicle/address information, mileage claim details
  - Travel/Miscellaneous-style repeatable claim rows with amount, receipt/invoice, remarks and attachment
- Training Period Change
- Performance self-assessment
- Quiz Assessment
- Offboarding
  - Uses **Completion Letter** terminology
- Documents
- Notifications

## Important prototype note

This project is intentionally **UI only**:

- No API calls
- No backend
- No authentication
- No database
- No real file uploads
- No persistence after page refresh

The `Demo Persona` selector in the top bar is only for previewing how the interface changes between **PROTÉGÉ** and **Industrial** trainees. In a real system, the trainee category should come from the authenticated trainee profile rather than asking the user to select it.

## Run locally

```bash
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Build

```bash
npm run build
```

## Suggested next steps

1. Replace mock data in `src/mockData.js` with API data later.
2. Confirm exact fields for Vehicle Information / Address in Mileage claims.
3. Confirm claim validation/calculation rules and predefined route distances.
4. Confirm leave-specific document requirements and leave balance rules.
5. Confirm the nine performance-assessment criterion labels.
6. Add a design system or component library if desired after the wireframe is approved.
# tms_ui
