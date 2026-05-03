Data Cleaning Decision: Order Status Filtering
We keep only orders with delivered status for the following reasons:
1. Retention analysis requires completed purchases
Our core question is: do customers come back after buying? A customer can only be retained if they actually received and experienced the product. Undelivered orders don't qualify.
2. Each dropped status has a clear reason:

canceled — customer or seller cancelled before fulfillment. No product experience.
unavailable — order was approved but never shipped. All 609 rows have NaN delivery date, confirmed in our inspection.
shipped — order is in transit, not yet received. Incomplete transaction.
invoiced — payment initiated but stuck. Never fulfilled.
processing — order never left the warehouse.
created / approved — early pipeline stages, far from delivery.

3. Data loss is acceptable
We drop ~3% of records (2963 rows out of 99441). This is a deliberate, minimal intervention — we preserve 96478 clean, completed transactions for analysis.
4. This is not arbitrary
We inspected each status category before making this decision. The filtering is driven by data, not convention.