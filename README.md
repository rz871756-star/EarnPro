# EarnPro

Full-stack rewards website starter for Render.

## Features
- Signup/login with hashed passwords
- PostgreSQL database
- User balance
- Tasks and sponsored-offer slots
- Referral code field
- Withdrawal requests
- Admin withdrawal list
- Mobile-friendly interface

## Render setup
1. Create a PostgreSQL database on Render.
2. Create a Web Service from this GitHub repository.
3. Build command: `npm install`
4. Start command: `npm start`
5. Add environment variables:
   - `DATABASE_URL` = Render PostgreSQL internal/external connection string as instructed by Render
   - `JWT_SECRET` = a long random secret
   - `ADMIN_EMAIL` = the email you will use for the admin account
6. Deploy.

## Important
This project does not pretend to move real money automatically. A real payout provider, identity/age requirements, business/legal compliance, and provider approval are separate steps. Sponsored/ad integrations must follow the chosen ad network's policies.
