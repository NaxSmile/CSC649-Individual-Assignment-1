# User Stories and Acceptance Criteria

Each story is linked to a requirement in [requirements.md](requirements.md).

## User Story 1 (linked to FR2)

> As a buyer, I want to filter search results by price, condition and buying format in one place, so that I can narrow down to suitable items faster.

**Acceptance criteria**

1. Opening the filter panel shows price range, condition and buying format together on one screen.
2. After applying filters, the results list shows only items that match all selected filters.
3. Choosing "Clear all" removes every filter and shows the original results.

## User Story 2 (linked to FR3)

> As a buyer, I want to see the item price, shipping cost and total price on each search result, so that I can compare the real cost of items without opening each listing.

**Acceptance criteria**

1. Every search result card shows three values: item price, shipping cost and estimated total.
2. The estimated total equals the item price plus the shipping cost.
3. For items with free shipping, the card displays "Free shipping" and the total equals the item price.

## User Story 3 (linked to FR6 and FR7)

> As a buyer, I want a short checkout with clear error messages, so that I can pay without confusion or having to restart.

**Acceptance criteria**

1. A buyer can move from the cart to the order confirmation screen in no more than 3 steps.
2. When a required field is missing or invalid, the screen shows a message that names the field and explains how to fix it.
3. Information already entered is kept after an error and is not erased.
