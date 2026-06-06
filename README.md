# Okta React Custom Login Exploration

This repo is a React-based authentication exploration using Okta's React SDK, Okta Auth JS, and the Okta Sign-In Widget. It demonstrates how a single-page React application can support a custom embedded login experience with Okta-backed OIDC authentication.

## Overview

Authentication products are easiest to understand when implemented in a working app. This project explores a custom-login pattern where the application owns more of the login UX while relying on Okta for identity, token issuance, and session handling.

## What it demonstrates

- React single-page app authentication
- Okta React SDK integration
- Okta Auth JS usage
- Okta Sign-In Widget customization
- React Router-based protected navigation patterns
- Environment-based OIDC configuration
- Developer-facing identity integration workflow

## Tech stack

- React 17
- Create React App
- Okta React SDK
- Okta Auth JS
- Okta Sign-In Widget
- React Router
- Semantic UI React
- dotenv
- ESLint / Airbnb config

## Product framing

The product value of this project is understanding how much control developers can have over authentication UX while still delegating security-sensitive identity functions to a platform provider.

It is relevant for product work involving:

- Embedded login
- Hosted vs custom authentication UX
- Developer experience for identity integrations
- OAuth/OIDC setup flows
- Frontend authentication patterns

## Running locally

```bash
npm install
npm start
```

The app expects Okta/OIDC configuration through environment variables such as issuer and client ID.

## Portfolio positioning

This should be presented as an identity integration exploration, not as a standalone product. It supports the broader story that I understand both the PM and implementation sides of authentication systems.

## Status

Authentication sample/exploration. Useful as supporting evidence for identity-platform experience.