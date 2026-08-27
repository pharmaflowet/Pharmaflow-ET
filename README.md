# PharmaFlow ET

PharmaFlow ET is a Windows desktop pharmacy-management system built for Ethiopian pharmacies. It combines point-of-sale, inventory, accounting, clinical resources, adverse-drug-event reporting, HR and payroll, bilingual English/Amharic guidance, Ethiopian-calendar support, and local-network operation in one application.

## Current desktop release

- **Version:** 1.0.3
- **Publication date:** 27 August 2026 (Nehase 21, 2018 E.C.)
- **Release type:** Optional update
- **Platform:** Windows x64
- **Package:** Self-contained installer; users do not need to install .NET separately
- **Installer:** `PharmaFlowEt-Setup-1.0.3.exe`
- **SHA-256:** `65270980780e5216beaa9d96af4e41d6e8a64536a8069d8f1a8f4123bec63dce`

Version 1.0.3 is an optional update. Existing users on a supported version may dismiss the update prompt and continue using their current installation.

## What is new in version 1.0.3

- A branded splash screen now appears immediately while PharmaFlow ET prepares local data and the workspace.
- The splash screen includes a continuously animated blue loading indicator, reassuring users that startup is still progressing.
- Question-mark buttons on the login and main windows provide direct access to the built-in bilingual Help system.
- The login window now displays current PharmaFlow ET support and contact information.

## Installing or updating

1. Download `PharmaFlowEt-Setup-1.0.3.exe` from the PharmaFlow ET [GitHub Releases](https://github.com/pharmaflowet/Pharmaflow-ET/releases) page after the 1.0.3 release is published.
2. Close PharmaFlow ET if it is running.
3. Run the installer and follow the setup prompts.

The installer uses the existing PharmaFlow ET installation identity and is designed to retain business data, settings, and licensing information during an update. Maintaining a current backup before installing any update is recommended.

## Main capabilities

- Point of sale, credit sales, and sales reporting
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

PharmaFlow ET is currently distributed as a beta/trial release. Installing or using the application indicates acceptance of the [software license agreement](installer/LICENSE.txt). Version 1.0.3 is identified there with its publication date and optional-update classification.

## Building the Windows installer

From the repository root, run:

```powershell
.\build-installer.ps1
```

The release script restores the Windows dependencies, publishes the self-contained x64 application, verifies required assets, builds the Inno Setup installer, and writes both the installer and optional-update `version.json` manifest to the `dist` folder.
