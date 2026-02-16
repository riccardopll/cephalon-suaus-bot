# Cephalon Suaus

Discord bot for quick Warframe item lookups.

## Commands

- `/s <search>`: item stats/details from [warframestat.us](https://api.warframestat.us/)
- `/m <market>`: sell orders from [warframe.market](https://warframe.market/)
- `/about`: project info embed

## Install

1. Install dependencies:
   ```bash
   npm install
   ```
2. Create `.env`:

   ```bash
   TOKEN=your_discord_bot_token
   CLIENT_ID=your_discord_application_id
   DEV_GUILD_ID=your_test_server_id
   global=false
   ```

3. Build and run manually with env file:

   ```bash
   docker build -t cephalon-suaus .
   docker run --rm --env-file .env cephalon-suaus
   ```
