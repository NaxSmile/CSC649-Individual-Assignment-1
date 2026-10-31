# Requirements

In the requirements below, **"the system"** means the **redesigned eBay mobile app buyer experience, as shown in the prototype**.

## B1. Functional Requirements

| ID | Requirement |
|----|-------------|
| FR1 | The system shall display a search bar on the home screen that is visible without scrolling. |
| FR2 | The system shall let buyers apply filters for price range, item condition and buying format from a single filter panel. |
| FR3 | The system shall show the item price, the shipping cost and the estimated total price on every search result card. |
| FR4 | The system shall display the seller's feedback score and positive-feedback percentage on the listing page above the buying action. |
| FR5 | The system shall show the time remaining and the current highest bid on every auction listing. |
| FR6 | The system shall let buyers complete checkout from the cart in no more than 3 steps. |
| FR7 | The system shall display an error message that states what is wrong and how to correct it when a checkout input is invalid. |
| FR8 | The system shall let buyers save a filter set for reuse in later searches. |

## B2. Non-Functional Requirements

| ID | Type | Requirement |
|----|------|-------------|
| NFR1 | Usability | The redesigned prototype shall achieve an average System Usability Scale (SUS) score of at least 68 across at least 5 test participants. |
| NFR2 | Usability | At least 4 out of 5 test participants shall complete the task "find a used item under a given price and add it to the cart" within 120 seconds. |
| NFR3 | Accessibility | Body text and interactive elements shall have a colour contrast ratio of at least 4.5:1 against their background. |
| NFR4 | Accessibility | All tappable elements shall have a touch target of at least 48 × 48 dp. |
| NFR5 | Performance | The system shall show visible feedback (screen change, loading indicator or button state) within 1 second of every tap. |
| NFR6 | Security and privacy | The system shall mask all but the last 4 digits of a payment card number on every screen where it is displayed. |

## Traceability

| User story | Functional requirement | Related non-functional requirement |
|------------|------------------------|------------------------------------|
| US1 | FR2 | NFR2, NFR4 |
| US2 | FR3 | NFR3 |
| US3 | FR6, FR7 | NFR5, NFR6 |

The user stories are in [user-stories.md](user-stories.md).

## Planned Improvements Beyond a Visual Refresh

| # | Improvement | Why it helps | Requirement |
|---|-------------|--------------|-------------|
| 1 | Total-price transparency on result cards | Removes the need to open each listing to learn the real cost | FR3 |
| 2 | Seller trust summary shown before the Buy or Bid button | Reduces uncertainty for first-time buyers | FR4 |
| 3 | Auction status block | Helps newcomers understand how bidding works | FR5 |
| 4 | Single filter panel and saved filters | Cuts repeated effort for returning buyers | FR2, FR8 |
| 5 | Shorter checkout with clear error recovery | Reduces abandoned purchases and frustration | FR6, FR7 |
| 6 | Accessibility pass | Makes the app usable by more people and in more conditions | NFR3, NFR4 |
