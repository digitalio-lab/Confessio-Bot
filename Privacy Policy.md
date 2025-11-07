## Privacy Policy

**Last updated:** November 7, 2025

This Privacy Policy explains what information the Bot collects, how it is used, stored, and your rights regarding that data.

### 1. Information We Collect
To provide functionality, the Bot stores and processes:
- Server configuration data (GuildConfig): guildId, confessionChannels, logChannel, aesthetic preferences, etc.
- Moderation data: blockedUsers lists per server.
- Premium & payment data: premiumEmail linked to guildId, and temporary PendingPayment data from Ko-fi webhooks (email, transaction ID, amount) for payment verification.
- Activity data: confessionCount and lastUsed timestamp per server.

We do not store confession content in our database. Confession content is relayed through the Bot to Discord’s API for posting.

### 2. How We Use Information
Data is used to:
- Provide core Bot features (posting and logging confessions).
- Verify and manage premium subscriptions.
- Enable server administrators to moderate content.
- Monitor bot health and activity.

### 3. Data Sharing
We do not sell, trade, or share personally identifiable information with third parties, except when required by law. Data is stored in a secure MongoDB database.

### 4. Data Retention
- GuildConfig is retained while the Bot is active in the server. If the Bot is removed, we may mark the configuration as inactive (isActive: false).
- PendingPayment records are retained to verify and reconcile payments; processed payments are marked processed: true.

### 5. Your Rights
You can request deletion of your server’s data. If you remove the Bot from your server, contact us to request permanent deletion of the GuildConfig and related data.

### 6. Contact
For privacy questions or data deletion requests, contact: contact@confessio.click