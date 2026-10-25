# Halfhour

`tariffs.json` holds the Irish dynamic-tariff supplier rates that the Halfhour app reads, served at
https://fractaldoctor.github.io/Halfhour/tariffs.json.

Each figure is read by hand from the supplier's own published price list, linked in its `sourceURL`, and dated in its `readOn`.
Rates are ex VAT. `vatRate` and `capCents`, the CRU's cap on the dynamic part, apply to every supplier.

Halfhour is not affiliated with any electricity supplier. Supplier names belong to their owners.
