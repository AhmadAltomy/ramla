# 📋 Current Power

## Mobile Application

### Authentication

- [ ] Fix the register new user with email functionality to ensure sending the right data to the server.
- [ ] Fix the error handling and user feedback for the login and signup processes.
- [ ] Implement "Apple Sign In" functionality for iOS users.

### Theme & Design

- [ ] Modify the theme of the app to match the Current Power branding.
- [ ] The Charging History page should have a title on the top of the page.
- [ ] Enhance the station marker design to not include icon just a circle with the number of active chargers available in the station.
- [ ] Fix the colors of the status of the charger point (eg. Avilable now it's red not green).

### Bugs

- [ ] Login & Signup page has scrolling issues.
- [ ] Fix the Each child in a list should have a unique "key" prop warning in the console. when open the station sheet.

### Vechicle Management

- [ ] User can (add, edit, delete) vehicles that connected to the backend.
- [ ] User can view the selected car details in the Home screen.

### Home Screen (Map View)

- [ ] Remove the extra details for the selected car. We don't want the battery, range details. Just the car name.
- [ ] Remove the Layers button from the Home Screen (Map View).

### Filter Results

- [ ] Redesign the filter results page to match the data provided by the backend.
- [ ] Implement the filter results page to get the data from the backend.
- [ ] When the user selects a filter, the map should update to show the filtered results of the charging stations.

### Station And Charging

- [ ] The station marker should have the available connector numbers not the total number of chargers in the station.
- [ ] Remove the three dots from the station details page.
- [ ] Fix display the prices for the charging stations in the station details page.
- [ ] We want to plan away to handle keep the session alive for the user when they open the app again or when they close the app and open it again.
- [ ] Implement the Power of the charger point in the Charging point and start charging page.

### Bookmarks

- [ ] Implement the functionality to allow users to bookmark charging stations.

### For Testing

- [ ] Test the permissions for the app when the user opens the app for the first time check what the location permissions and check if the user not accept the location permission.

### Search

- [ ] Remove the Recent searches static data and make sure it's dynamic.
- [ ] Implement the real data and real functionality for the search page to get the data from the backend.

## Admin portal

### Station Management

- [ ] Fix the error in the station management when trying to attach a charger point to a station. When creating a new charger point the station attach it but the problem is when trying to attach already registered charger point to the station it not working.
- [ ] We can change the location of the station with a map not just the text input for latitude and longitude.
- [ ] We need a list of chargers table with a view to show the details of the charger point and the connectors for the charger point.
- [ ] Make sure the the user can edit the charger point price.

### Dashboard

- [ ] Get the correct data from the backend for the dashboard.
- [ ] Remove the not needed views from the dashboard.
- [ ] Implement the functionality to show the total number of stations, total number of chargers, and total number of users in the dashboard.

### Analytics

- [ ] Check the analytics data and make sure it's correct.
- [ ] Display the user trends, revenue and feature usage in the analytics page.

### User Management

- [ ] Implement the create user feature.
- [ ] Check if the user edit or create can get the roles from the backend.

### Central Management

- [ ] Implement the transactions from the backend to the central management system.
- [ ] Implemet the invoices for each transaction from the backend to the central management system.
- [ ] View the details for each transactions and invoices in the central management system.
- [ ] We can filter the transactions and invoices by date, user, station, charger point, and status.

### Payment Management

- [ ] Implement the data and functionality for the Transactions, Refunds, Payment customers, payment methods, and payment gateways.
- [ ] Check the payment methods and gateways data and make sure it's correct.

## Central System for the Charging Stations Owners

- [ ] Create a new central system that for the charging stations owners to view the dashboard, analytics.
- [ ] Implement the functionality to view the transactions and invoices for each charging station.
- [ ] Implement the station owner user credentials to access the central system. and view their stations, transactions, and invoices.
- [ ] Implement the login for the central system for the charging stations owners.

## Landing page

- [ ] Implement the landing page for the Current Power app.
- [ ] Make sure the landing page is responsive and works well on mobile devices.

## Help & Support

- [ ] Create the help and support data.
- [ ] Implement the editing for the help and support data from the admin portal.
- [ ] Make sure the app can display the help and support data in the app.

## Deployment & Publishing Checklist

### 1. Legal & Compliance

- [ ] Create and publish a Privacy Policy page (required for both stores).
- [ ] Create and publish a Delete Account page/feature (required for both stores).
- [ ] Ensure GDPR and other legal compliance (as required).

### 2. Backend & Environment Preparation

- [ ] Prepare and deploy the Backend, Admin Portal, and any required APIs to production.
- [ ] Set up production environment variables and configuration for mobile app, backend, and portal.

### 3. Developer Accounts & Store Setup

- [ ] Register developer accounts for Google Play Console and Apple App Store Connect.
- [ ] Configure app signing (keystore for Android, certificates/profiles for iOS).

### 4. App Assets & Metadata

- [ ] Update app icons and splash screens for production.
- [ ] Prepare and finalize app metadata (app name, description, keywords, categories, etc.).
- [ ] Capture and upload required screenshots for all device sizes (Android & iOS).
- [ ] Prepare and upload app preview videos (if required).

### 5. Features & Integrations

- [ ] Set up and verify in-app purchase or subscription products (if applicable).
- [ ] Integrate and test analytics, crash reporting, and monitoring tools.
- [ ] Set up and test push notifications in production.

### 6. Testing & Quality Assurance

- [ ] Test the app thoroughly on real devices (Android & iOS) and emulators/simulators.
- [ ] Run all automated and manual tests for the latest changes.

### 7. Store Compliance & Submission

- [ ] Check and comply with all Google Play and App Store guidelines (content, privacy, security, etc.).
- [ ] Prepare and review the app store listing for both stores.
- [ ] Submit the app for review on Google Play and App Store.
- [ ] Respond to any review feedback and make necessary changes.

### 8. Post-Launch & Monitoring

- [ ] Set up post-launch monitoring and support (crash, analytics, user feedback).
- [ ] Set up app versioning and release notes for each release.
- [ ] Create and document revenue rates, commission, and financial reporting setup.
