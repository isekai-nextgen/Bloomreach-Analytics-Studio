# Privacy Policy for Bloomreach Analytics Studio

**Last Updated:** November 2025

## Overview

Bloomreach Analytics Studio is a developer debugging tool that displays Bloomreach/Exponea analytics data in Chrome DevTools. This privacy policy explains what data the extension accesses and how it is handled.

## Data Access

### What Data is Accessed?

The extension reads and displays the following information that exists in Bloomreach SDK objects on web pages you visit:

- **Bloomreach Configuration**: API endpoints, tokens, SDK settings, data layer configuration, experimental features
- **Event Data**: Real-time tracking events (page visits, custom events, identify calls, banner views, experiment triggers)
- **Customer Identifiers**: Email addresses (via `window.exponea.getEmail()`), customer IDs, cart IDs, session IDs, visitor IDs
- **Platform Data**: E-commerce platform identifiers (Shopify IDs, Magento IDs, WooCommerce IDs, etc.)
- **SDK Versions**: Bloomreach/Exponea script versions and integration versions
- **Cookies**: Bloomreach/Exponea tracking cookies (only when cookie consent is given)
- **Consent Status**: Cookie consent state from OneTrust, Optanon, or custom consent systems

### How is Data Used?

All data is displayed **locally in Chrome DevTools** for debugging purposes only. The extension:

- Shows data in the DevTools panel on your device
- Does NOT store data permanently
- Does NOT transmit data to external servers
- Does NOT send data to third parties
- Does NOT create databases or logs

## Data Storage

### Local Storage

The extension stores only UI preferences locally in your browser's localStorage:

- **UI Preferences**: Which event cards are expanded in the timeline view (stored as `bloomreach_expanded_events`)

This preference contains no personal information - only UI state for your convenience. No Bloomreach data, customer information, or website content is stored permanently.

### No Permanent Data Collection

All Bloomreach data is processed in memory during your debugging session. When you close DevTools or refresh the page, the data is cleared. No data is retained beyond your current browser session.

### Export Feature

The extension includes an "Export Timeline" feature that allows you to download event data as a JSON file to your local device. This export is entirely under your control - you choose when to export, and the file is saved directly to your computer. The extension does not access or transmit exported files.

## Data Transmission

**Zero Data Transmission**: The extension has no backend servers, no analytics tracking, and no external data transmission of any kind. All processing happens locally in your browser. The extension uses only local browser APIs (`window.postMessage`, Chrome extension messaging) to communicate between components - all communication stays within your browser.

## Permissions Explained

- **activeTab**: To read Bloomreach SDK objects from the current tab
- **storage**: To save your UI preferences locally
- **scripting**: To inject monitoring script into page context where Bloomreach SDK runs
- **tabs**: To communicate between DevTools and content scripts
- **Host permissions**: To access Bloomreach on any website domain you're testing

## Cookie Consent and Privacy Compliance

The extension respects cookie consent settings and will display "No Tracking" when:
- Cookie consent has been denied on the website
- Bloomreach/Exponea SDK indicates tracking is disabled
- OneTrust, Optanon, or custom consent systems show no consent

When consent is denied, the extension does not display customer data, cookies, or tracking events, matching the behavior of Bloomreach's official console.

## User Control

- Data is only accessed when you actively open Chrome DevTools and navigate to the "Bloomreach Analytics Studio" tab
- The extension does not run or access data in the background
- You control when and which websites you inspect
- No automatic data collection or background monitoring
- All data access is user-initiated through DevTools

## Third-Party Services

The extension does not use any third-party analytics, tracking, or data collection services.

## Contact

For privacy questions, contact: **isekai.nextgen.apps@gmail.com**

## Updates

This privacy policy may be updated. The "Last Updated" date will reflect the latest version.

