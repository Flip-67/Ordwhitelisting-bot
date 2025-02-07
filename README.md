# Ordwhitelisting-bot
WhiteList bot for Discord 
We made this bot to be free for the community! 
So enjoy and we will continuse to add more features soon. 


Getting Started

1. Adding the Bot to Your Server

Invite the Ord Whitelist Bot using the provided Discord invite link.

Ensure the bot has the necessary permissions to function correctly.

2. Basic Setup

Use /configure channel #channel-name to set the whitelist submission channel.

Use /configure status open to open whitelist submissions.

Use /configure maxwallets <number> to set the maximum allowed wallet submissions.

Use /configure submittedrole @role-name to assign a role when a user submits a wallet.

Commands Overview

Whitelist Management

/add_wallet @user <wallet_address> - Add a BTC wallet for a user.

/remove_wallet @user - Remove a user’s wallet from the whitelist.

/count_wallets - Display the total number of submitted wallets.

/download_wallets - Download all submitted wallets as a CSV file.

Configuration & Admin Commands

/configure <setting> <value> - Adjust bot settings (e.g., set a whitelist channel, max wallets, etc.).

/viewconfig - View current bot configuration.

/send_submissionpanel - Post the submission panel in the designated channel.

/download_auditlog - Download a log of all wallet-related actions.

/bulk_import - Import a list of wallets for verification.

Security & Privacy

The bot stores only necessary information related to wallet submissions.

Wallet addresses are only used for whitelist verification.

Admins can request wallet data removal by deleting the user’s submission.

Support

If you encounter issues, contact your server administrator.

For further help, visit the bot’s support page or developer contact details.

Enjoy using Ord Whitelist Bot!
