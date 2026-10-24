# Install Obsidian Second Brain on Android

This repository contains a starter kit. It does **not** install the Obsidian app or create a synced private vault automatically.

## Safe setup

1. Install **Obsidian** from the official site: https://obsidian.md/mobile
2. Open Obsidian on Android and choose **Create new vault**.
3. Name it `Ade-Second-Brain`.
4. Save it in a folder on your device that you can find again. Do not create the personal vault inside a public GitHub repository.
5. Create these folders inside the vault:
   - `00-Inbox`
   - `01-Dashboard`
   - `02-Projects`
   - `03-Areas`
   - `04-Resources`
   - `05-Logs`
   - `99-Archive`
   - `Templates`
6. Copy the Markdown templates from this repository's `second-brain/templates/` folder into your vault's `Templates` folder.
7. In Obsidian, open **Settings → Core plugins → Templates**, enable it, then set **Template folder location** to `Templates`.
8. Create a note named `Home` and paste the content from `second-brain/Home-Template.md`.
9. Keep private notes, trading account details, API keys, passwords, recovery phrases and broker credentials out of this public repository.

## Optional GitHub backup

If you want Git version history or multi-device sync, create a **private** repository specifically for the vault and check its visibility before uploading anything. Do not push a local vault to a public repository. Obsidian Sync is another option and may require a paid plan.

## Recommended daily routine

- Capture loose thoughts in `00-Inbox`.
- Keep active work in `02-Projects`.
- Use the trading research template for analysis and journal entries; record hypotheses separately from verified market data.
- Review notes weekly and move completed or inactive material to `99-Archive`.

## Scope and safety

This starter kit is documentation and templates only. It does not connect to MT5, place trades, change broker settings, or store credentials.