# PharmaFlow ET 1.0.6

Release date: 5 October 2026 (Meskerem 25, 2019 E.C.)
Release type: Optional update; Windows x64, self-contained beta/trial release.

## What's new

- Daily Sale Details now shows Total COGS and Gross Profit Total after Sale Price Total and before Dispenser. Expanded item rows show Cost Line Total and Gross Profit next to the sale line total.
- Product Summary now shows Total COGS and Gross Profit after Total Revenue.
- Costs use the purchase cost recorded at the time of sale. Line cost is quantity multiplied by historical unit cost; gross profit in the new columns is displayed sale revenue, including VAT, minus recorded cost.
- English and Amharic translations cover additions since 1.0.3 and missing labels on updated inventory, batch, sales report, dashboard, backup, licensing, startup, and updater screens. Clinical conditions and resource content retain their original language.
- Live language switching refreshes dynamic labels, alerts, dropdowns, trial status, and update progress while preserving stored choices and selections.
- Includes the previous shelf/store inventory fix, configurable stock alerts, newest-first Sale Hub entries, in-app installer downloads, and 10-day trial.

## Installation

Back up business data, close PharmaFlow ET, then run `PharmaFlowEt-Setup-1.0.6.exe`. Update the server and workstations together in local-network installations. The installer retains the existing installation identity and performs an in-place update.

Versions before 1.0.5 open the browser download link. Version 1.0.5 and later download the update inside the app, verify it, and open the installation wizard. The trial remains 10 days from the original installation date.

## Publication checklist

1. Publish in `pharmaflowet/Pharmaflow-ET` using tag **Release7**, title **PharmaFlow ET 1.0.6**, and the latest-release setting.
2. Upload `dist/1.0.6/PharmaFlowEt-Setup-1.0.6.exe`, `SHA256SUMS.txt`, and `version.json`. Verify the installer size and SHA-256 against the manifest.
3. Verify the direct installer link: `https://github.com/pharmaflowet/Pharmaflow-ET/releases/download/Release7/PharmaFlowEt-Setup-1.0.6.exe`.
4. After the installer is publicly available, update the website's download link and root `version.json` using the existing Netlify deployment workflow. The update is optional (`mandatory: false`) and the minimum supported version remains 1.0.1.
5. Preserve previous releases and installer assets. Publish the updated README, changelog, and license with the release documentation.

The build script prepares the installer and manifest; it does not upload or deploy them.
