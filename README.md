# Social Citations Company public frontend R84

Production split architecture:
- Public custom-domain frontend: GitHub Pages.
- Secure commerce/order/support backend: Floot.
- Payments: Stripe-hosted Checkout.
- Buy links navigate to the Floot backend, which creates a session and immediately redirects to Stripe.
- No Stripe secrets exist in this repository.
- Free PDFs remain free and do not require signup.
- The backend re-verifies Stripe payment/refund/dispute state before fulfillment.
