# Changelog

## 1.0.6 — 5 October 2026

Optional Windows x64 update (Release7).

- Added Total COGS and Gross Profit Total to each sale in Daily Sale Details, after Sale Price Total and before Dispenser.
- Added Cost Line Total and Gross Profit to the expanded sold-item grid. Line cost is quantity multiplied by the historical purchase cost per unit.
- Added Total COGS and Gross Profit to Product Summary, after Total Revenue.
- These gross profit columns subtract recorded cost from displayed sale revenue, including VAT. Historical sale costs are retained when current product costs change.
- Added English and Amharic translations for components introduced since 1.0.3 and missing labels on the updated screens, including inventory summaries, filters and notifications, batch controls, dashboard alerts, sales reports, backup settings, trial status, splash screen, and updater messages.
- Fixed live language switching for dynamic labels and download progress. Translated dropdown displays preserve the values used by purchasing, filtering, and accounting.
- Clinical conditions and resource content retain their original language.
- Retained the 10-day trial and all fixes introduced in 1.0.5.

## 1.0.5 — 1 October 2026

Optional Windows x64 update (Release6).

- Made shelf and store quantities authoritative for inventory availability; removed legacy Available and Initial Quantity batch fields. Older batches missing location fields are upgraded automatically.
- Made stock alert colors and notifications respect saved product thresholds, including zero.
- Placed newly added Sale Hub items at the top of the new order grid.
- Added in-app installer downloads with progress, file size and SHA-256 verification, followed by opening the installation wizard.
- Shortened the free trial to 10 days from the original installation date, including existing unlicensed installations.

## 1.0.4 — 24 September 2026

Optional Windows x64 update (Release5).

- Added compact inventory summaries, stock and expiry filters, and persistent inventory notifications.
- Added stocked-batch expiry highlighting, badges, and dashboard summaries, with warnings below 180 days and urgency below 30 days.
- Kept newly registered products neutral until they receive stock; displayed stockouts in red and low stock in orange.
- Improved supplier fields and credit supplier synchronization in stock entry; allowed blank received batch numbers.
- Added selling units to inventory logs and improved grid spacing and header alignment.
- Corrected the cashier shown for recent credit sales and prevented embedded-server shutdown from blocking desktop exit.
- Refined splash screen corners and shading.

## 1.0.3 — 27 August 2026

Published desktop release (Release4); baseline for the localization review in 1.0.6.
