# PharmaFlow ET

PharmaFlow ET is a Windows desktop pharmacy-management system built for Ethiopian pharmacies. It combines point-of-sale, inventory, accounting, clinical resources, adverse-drug-event reporting, HR and payroll, bilingual English/Amharic guidance, Ethiopian-calendar support, and local-network operation in one application.

## Current desktop release

- **Version:** 1.0.6
- **Publication date:** 5 October 2026 (Meskerem 25, 2019 E.C.)
- **Release type:** Optional update
- **Platform:** Windows x64
- **Package:** Self-contained installer; users do not need to install .NET separately
- **Installer:** [PharmaFlowEt-Setup-1.0.6.exe](https://github.com/pharmaflowet/Pharmaflow-ET/releases/download/Release7/PharmaFlowEt-Setup-1.0.6.exe)
- **SHA-256:** See `SHA256SUMS.txt` in the [release assets](https://github.com/pharmaflowet/Pharmaflow-ET/releases/tag/Release7).

Version 1.0.6 is an optional update. Existing users on a supported version may dismiss the update prompt and continue using their current installation.

## What is new in version 1.0.6

- Daily Sale Details shows **Total COGS** and **Gross Profit Total** after Sale Price Total and before Dispenser. Expanded sold-item rows show **Cost Line Total** and **Gross Profit** beside the sale line total.
- Product Summary shows **Total COGS** and **Gross Profit** after Total Revenue. Costs use the purchase costs recorded at the time of sale, rather than today's product cost. Gross profit in these columns is displayed sale revenue, including VAT, minus recorded cost.
- English and Amharic localization now covers additions since 1.0.3 and missing labels on the updated inventory, sales report, batch, dashboard, backup, licensing, startup, and updater screens. Clinical conditions and resource content keep their original language.
- Live language switching refreshes dropdown labels, stock alerts, trial status, and update download progress while preserving stored dropdown values and selections.

The current release also includes the improvements from 1.0.5:

- Inventory availability now uses shelf and store balances. Older batches without those fields are upgraded automatically.
- Stock alerts use saved product thresholds, including zero.
- Newly added Sale Hub products appear at the top of the new order grid.
- Updates download inside the app with progress and checksum verification, then open the installer wizard.
- The free trial lasts 10 days from the original installation date, including for existing unlicensed installations.

## Installing or updating

1. Download [PharmaFlowEt-Setup-1.0.6.exe](https://github.com/pharmaflowet/Pharmaflow-ET/releases/download/Release7/PharmaFlowEt-Setup-1.0.6.exe) from GitHub Releases, or use the app's update prompt.
2. If downloading manually, close PharmaFlow ET if it is running.
3. Run the installer and follow the setup prompts.

The installer uses the existing PharmaFlow ET installation identity and is designed to retain business data, settings, and licensing information during an update. Maintaining a current backup before installing any update is recommended.

## Main capabilities

- Point of sale, credit sales, and sales reporting with sale-level and product-level cost and gross profit
- Product, batch, expiry, supplier, disposal, and stock-transfer management
- Clinical references, medicine interaction checks, and EFDA-based adverse-drug-event reports
- Cash, bank, ledger, receivable, liability, fixed-asset, and prepaid accounting
- Employee records, attendance, payroll, and configurable permissions
- English and Amharic interface with Gregorian and Ethiopian calendar support
- Single-PC and local-network server/client operation
- Scheduled and manual database backups

For the full feature overview, see [Pharmaflow Et.md](Pharmaflow%20Et.md).

## Support

- Email: [pharmaflow.et@gmail.com](mailto:pharmaflow.et@gmail.com)
- Telegram: [@pharmaflowet](https://t.me/pharmaflowet)
- Phone: +251 988 52 25 12
- Additional contact: +251 799 35 71 71

## License

PharmaFlow ET is currently distributed as a beta/trial release with a 10-day trial. Installing or using the application indicates acceptance of the [software license agreement](LICENSE.txt). Version 1.0.6 is identified there with its publication date and optional-update classification.

Release history is in [Changelog.md](Changelog.md). See [the 1.0.6 release notes](RELEASE-NOTES-1.0.6.md).
