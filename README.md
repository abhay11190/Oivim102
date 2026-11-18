# SellerSmart Support Bot

Deploy as a Render Background Worker using this repository/Blueprint.

Set the `BOT_TOKEN` environment variable in Render. Never commit the token to GitHub.

Commands:
- `/help`, `/id`
- `/setpinduration 2h`, `/pinduration`
- `/setemoji welcome CUSTOM_EMOJI_ID`
- `/setemoji pin CUSTOM_EMOJI_ID`
- `/admin`, `/unadmin`, `/ban`, `/unban`, `/mute`, `/unmute`

For moderation commands, reply to a member's message or append their numeric Telegram user ID, e.g. `/ban 123456789`.

The bot must have the matching admin permissions:
- Add New Admins for `/admin` and `/unadmin`
- Ban Users for `/ban` and `/unban`
- Restrict Members for `/mute` and `/unmute`
- Pin Messages for pin features

The bot does not delete advertisements, links, Telegram Stars links, or OTC posts.
