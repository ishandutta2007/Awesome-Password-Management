# Awesome-Password-Management

## Top Password Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Password Vaults, Credential Sharing, Autofill, Passkeys & Secure Secrets Management*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Password Management**. These tools securely store, generate, autofill, and share passwords and other secrets for individuals and teams, with strong emphasis on encryption, zero-knowledge architecture, and cross-platform access.



**Examples** include 1Password, Bitwarden, LastPass, Dashlane, Keeper, NordPass, RoboForm, Enpass, Passbolt, and Zoho Vault (the category leaders).



**Open-source emphasis**: Password management has one of the strongest open-source ecosystems. **Bitwarden**, **Vaultwarden**, **Passbolt**, **KeePassXC**, and related projects are widely trusted and actively maintained. This section is heavily expanded with these options.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[1Password](https://1password.com/)**  

  Premium password manager known for polished UX, strong security model (Secret Key + master password), Travel Mode, and excellent family/team features.



- **[Bitwarden](https://bitwarden.com/)**  

  Popular open-source password manager with free and premium cloud plans, strong security, and broad platform support (also fully self-hostable).



- **[LastPass](https://www.lastpass.com/)**  

  Long-standing cloud password manager offering personal and business plans with autofill, sharing, and dark-web monitoring features.



- **[Dashlane](https://www.dashlane.com/)**  

  Feature-rich password manager with VPN, dark-web monitoring, and strong autofill capabilities for individuals and teams.



- **[Keeper](https://www.keepersecurity.com/)**  

  Security-focused password and secrets manager with zero-knowledge encryption, strong enterprise controls, and compliance features.



- **[NordPass](https://nordpass.com/)**  

  Password manager from the Nord Security family, emphasizing ease of use, biometric unlock, and cross-platform sync.



- **[RoboForm](https://www.roboform.com/)**  

  Established password manager and form filler with long history and solid desktop/browser integration.



- **[Enpass](https://www.enpass.io/)**  

  Offline-first password manager that stores data locally or on the user’s chosen cloud storage, with one-time purchase options.



- **[Passbolt](https://www.passbolt.com/)**  

  Open-source, team-oriented password manager focused on collaboration, auditing, and self-hosting (also offered as a hosted service).



- **[Zoho Vault](https://www.zoho.com/vault/)**  

  Password manager integrated with the Zoho ecosystem, suitable for individuals and organizations already using Zoho products.



## Open-Source GitHub Projects

- **[Bitwarden](https://github.com/bitwarden)**  

  Fully open-source password manager with official clients and server. Can be used via Bitwarden cloud or self-hosted.



- **[Vaultwarden](https://github.com/dani-garcia/vaultwarden)**  

  Lightweight, unofficial Rust implementation of the Bitwarden server API — fully compatible with official Bitwarden clients and ideal for self-hosting.



- **[Passbolt](https://github.com/passbolt)**  

  Open-source password manager designed for teams, with end-to-end encryption, fine-grained sharing, and strong auditing features. Self-hostable.



- **[KeePassXC](https://github.com/keepassxreboot/keepassxc)**  

  Modern, cross-platform, actively maintained open-source password manager based on the KeePass model. Local encrypted database (KDBX) with browser integration and TOTP support.



- **[KeePass / KeePassDX and ecosystem](https://keepass.info/)**  

  Classic open-source password manager family and compatible ports/apps for multiple platforms.



- **[pass (password-store)](https://www.passwordstore.org/)**  

  Unix-style password manager that stores credentials as GPG-encrypted files in a Git repository — highly scriptable and auditable.



- **[Psono and other team-oriented open vaults](https://github.com/)**  

  Additional open-source password managers focused on team sharing and self-hosting.



- **[Browser extension and client open projects](https://github.com/)**  

  Community clients and extensions that integrate with open password backends.



- **[Passkey and WebAuthn open tooling](https://github.com/)**  

  Libraries and helpers supporting modern passwordless and passkey workflows alongside traditional vaults.



- **[Secrets management open tools (related)](https://github.com/)**  

  Broader open projects for handling API keys and secrets that complement personal password managers in technical environments.



### Additional Strong Open-Source Options

- Using **Bitwarden** (cloud or self-hosted) or **Vaultwarden** for the best balance of usability and openness.

- Choosing **KeePassXC** when a fully offline, file-based solution is preferred.

- Deploying **Passbolt** for team credential sharing with audit trails.

- Combining **pass** with Git and GPG for highly technical, scriptable workflows.

- Accepting that polished UX, customer support, advanced dark-web monitoring, and some enterprise compliance features still favor commercial SaaS offerings (1Password, Keeper, etc.).



**Frameworks for building custom systems**: Self-host Vaultwarden or Passbolt → use official or open clients and browser extensions → enable 2FA / passkeys → back up encrypted vaults regularly → optionally sync via your own infrastructure. For pure local control, use KeePassXC with encrypted database files and optional secure sync. Commercial platforms remain convenient for users who prefer fully managed services and premium support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Password managers protect highly sensitive credentials. Always use strong unique master passwords (or passkeys), enable multi-factor authentication, keep software updated, and maintain secure backups. Self-hosted solutions require proper server security, TLS, and operational discipline. No tool eliminates all risk. This list is not security advice.



---

**Made for individuals, families, and teams who want strong, transparent control over their credentials.**

Let's keep secrets secure, private, and as open as practical.
