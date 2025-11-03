# Backend-SDK-Integration-Node.js
A complete Node.js SDK for the PhonePe Payment Gateway. Simplifies payment initiation, status checks, refunds, and webhook handling.
# PhonePe Node.js Backend SDK Integration

[![NPM Version](https://img.shields.io/npm/v/phonepe-nodejs-sdk.svg)](https://www.npmjs.com/package/phonepe-nodejs-sdk)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An unofficial Node.js SDK for server-side integration with the PhonePe Payment Gateway. This library simplifies the entire payment lifecycle, handling API calls, payment initiation, status checks, and secure JWT webhook verification.

## Features

-   **Simplified Payment Initiation:** Create new payment requests with a simple function.
-   **Payment Status Verification:** Easily check the status of any transaction.
-   **Refund Support:** Programmatically initiate refunds.
-   **Secure Webhook Handling:** Includes a utility to verify the JWT signature from incoming v2 webhook notifications.
-   **Modern JavaScript:** Built with async/await for clean, modern, non-blocking code.

## Prerequisites

-   Node.js v18.0.0 or higher
-   NPM
-   A PhonePe Merchant Account with active **Backend SDK** credentials:
    -   `MERCHANT_ID`
    -   `CLIENT_ID`
    -   `CLIENT_SECRET`

## Installation

```bash
npm install phonepe-nodejs-sdk
