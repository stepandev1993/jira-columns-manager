# Privacy Policy - Jira Columns Manager

Last updated: 2026-04-26

## Overview
Jira Columns Manager is a browser extension that helps users manage columns in Jira Issue Navigator.

The extension operates on your Jira domain and uses Jira's own APIs to load available fields and save your selected column layout.

## Data collection
This extension does **not** collect, sell, or share personal data for advertising.

This extension does **not** send your data to third-party servers controlled by the developer.

## Data access and processing
The extension may access data visible on:
- your Jira Issue Navigator pages (for example: `https://<your-jira-domain>/issues/?jql=*`)

Purpose of access:
- Read available Jira columns for selection UI.
- Save the current user's Jira column configuration.
- Refresh the issue table to reflect updated columns.

## Network requests
Requests are made only to your Jira instance:
- `GET /rest/gadget/1.0/availableColumns`
- `PUT /rest/api/2/user/columns`
- page/table refresh requests on the same Jira origin

No remote code is downloaded or executed at runtime.

## Storage
The extension does not use external databases and does not persist user data outside Jira APIs.

## Security
- Uses browser same-origin context for Jira requests.
- Uses existing Jira authentication session in the browser (`credentials: include`).

## User control
You can stop all processing at any time by:
- disabling or removing the extension in Chrome,
- or leaving the Jira issues page where the extension runs.

## Contact
If you have privacy questions or support requests, contact: Email: stepan.usa.acc1993@gmail.com
