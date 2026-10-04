# Social Citations Company website routing

The maintained storefront, product artwork, policies and order workspace live at https://social-citations-company.floot.app/ . Payments use Stripe-hosted Checkout.

This GitHub Pages repository preserves socialcitationscompany.com and the URLs already printed on tickets and booklets. Its HTML pages immediately forward visitors to the corresponding Floot page. GitHub Pages serves browser redirects, not HTTP 301 responses. Known ticket and refill routes have dedicated files; query strings and fragments are retained when JavaScript is available. Each known page also provides a fixed link and meta refresh fallback.

Maintain the existing CNAME and printed paths. The unknown-path 404 page forwards only to the fixed Floot origin. Do not add payment secrets, private documents or customer data to this public repository.

The current physical cover master is Merged R3. Product details and downloads are maintained in Floot so the company domain cannot drift into a second storefront. No new hosting service or reprinting is required for this route repair.
