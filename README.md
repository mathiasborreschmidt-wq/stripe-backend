# Stripe Backend til Premium-betalinger

Dette er en simpel Node.js backend til at oprette Stripe Checkout-sessioner for et månedligt abonnement (49 kr/md).

## Sådan bruges det:

1. Opret en Stripe-konto på https://stripe.com
2. Erstat `sk_test_XXXX` i `.env` med din hemmelige API-nøgle
3. Installér afhængigheder:
    npm install
4. Start serveren:
    node server.js
5. Deploy til Render: https://render.com

## Miljøvariabler
- `STRIPE_SECRET_KEY` (findes i din Stripe konto)
