# Problem Statement

## A1. Problem Statement

Casual and first-time buyers who use the eBay mobile app must work through crowded search results, multi-option filters and listing pages before they can decide whether an item is worth buying. In a walkthrough of the app on 28 October 2026 using Android, the application look too simple especially on homepage also the suggested selling item are not suitable with the interest user into. This slows buying decisions and makes it harder to judge the real price, the seller's trustworthiness and the item condition, which can lead to abandoned searches or purchases that the buyer later regrets. It matters because eBay listings vary widely auction or fixed price, new or used, different shipping costs, so an unclear interface directly reduces buyer confidence.

## Evidence to Collect

| # | Evidence | How to collect |
|---|----------|----------------|
| E1 | Task walkthrough of the current app | Do the four tasks below on own phone. Stop before paying. Do not complete a real purchase. |
| E2 | 5 to 10 public app-store reviews that mention usability problems | Read reviews on Google Play or the App Store and note the date and rating of each. |
| E3 | Heuristic evaluation findings | Apply Nielsen's 10 heuristics (see [technology-brief.md](technology-brief.md)) to 3 to 4 key screens. |

**Walkthrough tasks**

1. Search for a used item under a price you choose, and find its total cost including shipping.
2. Apply filters for price, condition and buying format.
3. Open a listing and find the seller's feedback information.
4. Add an item to the cart and go through checkout up to the payment screen only.

## A2. Users and Scope

### Primary users

| User | Description | Main need |
|------|-------------|-----------|
| Casual buyer | Occasional shopper who uses the app to find a specific item | Find items quickly and understand the real cost |
| First-time buyer | New to eBay and unfamiliar with auctions, conditions and seller ratings | Clear guidance and trust signals |
| Bargain or auction bidder | Buyer who bids on auctions or searches for deals | Clear bid status and time remaining |

### Stakeholders

| Stakeholder | Interest |
|-------------|----------|
| Sellers | Their listings must be easy for buyers to understand |
| eBay product and design team | Higher buyer confidence and fewer abandoned purchases |
| Users with accessibility needs | Readable text, usable touch targets |
| Course lecturer | Assesses the quality of the problem, requirements and technology explanation |

### In scope

- Buyer-side flows only: Home, Search, Filters, Search Results, Listing Page, Auction Information, Cart and Checkout (UI only).
- Low-fidelity wireframes and a mid or high-fidelity clickable prototype in Figma for the key screens.
- Heuristic evaluation of the current app, and a small usability test about 5 participants on the redesigned prototype.
- One mobile platform: Android.

### Out of scope

- Seller flows (Creating Listings, Managing Orders).
- Real backend, real payments, real data, and any code that connects to eBay's systems.
- Changes to eBay's business rules (fees, policies).
- Machine-learning recommendations and personalisation algorithms.
- Using eBay's logo or brand assets as if the work were official.
