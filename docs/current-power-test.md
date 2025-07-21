# 🧪 Current Power Testing Checklist

A comprehensive testing checklist to ensure all features and fixes in the Current Power project are working as expected. Organized by platform and feature area.

---

## Mobile Application

### Authentication

- [ ] Register new user with email: verify correct data sent to server, successful registration, and error handling.
- [ ] Login/Signup: test error feedback, invalid credentials, and successful login.
- [ ] Apple Sign In (iOS): test sign in, error cases, and fallback for unsupported devices.

### Theme & Design

- [ ] App theme matches Current Power branding on all screens.
- [ ] Charging History page displays correct title.
- [ ] Station marker: only a circle with number of active chargers, no icon.
- [ ] Charger point status colors: green for available, red for unavailable.

### Bugs

- [ ] Login & Signup page: no scrolling issues on all devices.
- [ ] No unique "key" prop warnings in station sheet.

### Vehicle Management

- [ ] Add, edit, delete vehicle: backend sync, UI update, error handling.
- [ ] Home screen: selected car details display only car name.

### Home Screen (Map View)

- [ ] No battery/range details for selected car.
- [ ] Layers button is removed.

### Filter Results

- [ ] Filter results page matches backend data structure.
- [ ] Map updates with filtered charging stations.

### Station and Charging

- [ ] Station marker shows available connector numbers.
- [ ] No three dots on station details page.
- [ ] Charging station prices display correctly.
- [ ] User session persists after app close/reopen.
- [ ] Charger point power shown in charging/start charging page.

### Bookmarks

- [ ] Users can bookmark/see bookmarked charging stations.

### Permissions

- [ ] On first launch, app requests location permission and handles denial gracefully.

### Search

- [ ] Recent searches are dynamic, not static.
- [ ] Search page fetches and displays real data from backend.

---

## Admin Portal

### Station Management

- [ ] Attach new and existing charger points to stations.
- [ ] Change station location using map input.
- [ ] Chargers table: view charger point and connector details.
- [ ] Edit charger point price.

### Dashboard

- [ ] Dashboard fetches correct data from backend.
- [ ] Only needed views are visible.
- [ ] Total stations, chargers, and users display correctly.

### Analytics

- [ ] Analytics data is accurate.
- [ ] User trends, revenue, and feature usage display correctly.

### User Management

- [ ] Create user feature works and roles are fetched from backend.
- [ ] Edit user feature works and roles are fetched from backend.

### Central Management

- [ ] Transactions and invoices fetched from backend.
- [ ] Transaction/invoice details viewable.
- [ ] Filter transactions/invoices by date, user, station, charger point, status.

### Payment Management

- [ ] Transactions, refunds, payment customers, methods, and gateways work and display correct data.

---

## Central System for Charging Station Owners

- [ ] Dashboard and analytics display correct data for station owners.
- [ ] Owners can view transactions and invoices for their stations.
- [ ] Station owner credentials work for login and access.
- [ ] Owners can only view their own stations, transactions, and invoices.

---

## Landing Page

- [ ] Landing page is implemented, responsive, and works on mobile devices.

---

## Help & Support

- [ ] Help and support data is created and displayed in the app.
- [ ] Admin portal allows editing help and support data.

---

## General

- [ ] All navigation flows work as expected.
- [ ] No critical or high-severity bugs remain.
- [ ] All user-facing text is proofread and clear.
- [ ] Accessibility checks (screen reader, color contrast, etc.).

---

**Note:** Mark each item as complete after thorough manual and/or automated testing. Add more specific test cases as new features are developed.
