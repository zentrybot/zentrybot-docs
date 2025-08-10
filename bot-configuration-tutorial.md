---
cover: .gitbook/assets/replicate-prediction-s2tv8vfqk5rme0crb4gtd3ba0w.jpg
coverY: 53.90657696400984
layout:
  width: default
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# ⚙️ Bot Configuration Tutorial

Complete guide for configuring ZentryBot through the dashboard.

## Bot Configuration Steps

### 1. Access Dashboard

* Open [zentrybot.xyz/dashboard](https://www.zentrybot.xyz/dashboard)
* Login using your XRPL wallet
* Ensure you have a Zentry NFT for access

### 2. Choose Bot Type

Select one of the two available bot types:

* **Token Tracker Bot**: To monitor token price and volume
* **NFT Tracker Bot**: To monitor floor price and NFT activity

### 3. Bot Configuration

#### For Token Tracker Bot:

**Token Currency** (Required)

* Enter the token currency code (example: USD, XRP)

**Token Issuer** (Required)

* Enter the token issuer address on XRPL
* Format: XRPL wallet address that issued the token

**Chart URL** (Optional)

* Link to token price chart
* Example: link to DEXScreener, CoinGecko, etc.

**Trade URL** (Optional)

* Link for trading the token
* Example: link to exchange or DEX

**Website URL** (Optional)

* Official project website

#### For NFT Tracker Bot:

**NFT Issuer** (Required)

* Wallet address that issued the NFT collection

**NFT Taxon** (Required)

* NFT collection taxon number on XRPL

**Collection URL** (Optional)

* Link to NFT collection page
* Example: link to marketplace like xrp.cafe

### 4. Topic ID (Optional) - Important!

**What is Topic ID?** Topic ID is an identification number for a specific topic within Telegram groups that use "Topics" or "Forum Groups" feature.

**How to Get Topic ID:**

1. **From Telegram Link:**
   * If you have a link like: `https://t.me/zentrybotz/915`
   * The number at the end of the link (915) is the Topic ID
   * In this example, Topic ID = **915**
2. **From Telegram App:**
   * Open the group that has topics
   * Click on the desired topic
   * Check the URL in browser or share the topic link
   * Take the number at the end of the link

**When to Use Topic ID:**

* ✅ Use if your Telegram group uses Topics/Forum feature
* ✅ If you want the bot to send messages to a specific topic
* ❌ Leave empty for regular groups (without topics)
* ❌ Leave empty if you want the bot to send to main chat

**Usage Example:**

* Topic link: `https://t.me/zentrybotz/915`
* Topic ID to fill: `915`
* Bot will send updates to topic with ID 915

### 5. Media URLs (Optional)

**Buy Media URL**

* Image/GIF link displayed when there's a purchase
* Format: Direct URL to image file

**Sell Media URL**

* Image/GIF link displayed when there's a sale
* Format: Direct URL to image file

### 6. Bot Activation

1. **Generate Activation Code**
   * Click "Generate Code" after configuration is complete
   * Copy the activation code that appears
2. **Add Bot to Group**
   * Invite @ZentryTokenBot or @ZentryNFTBot to your Telegram group
   * Give admin permissions to the bot
3. **Activation**
   * Type `/activate [activation_code]` in the group
   * Bot will start working after successful activation

## Important Tips

### ✅ Do's (What You Should Do)

* Ensure all required fields are filled correctly
* Use Topic ID only if the group uses Topics feature
* Test the bot in a small group first
* Save the activation code securely

### ❌ Don'ts (What You Should Not Do)

* Don't fill Topic ID if the group doesn't use Topics
* Don't use invalid URLs
* Don't share activation codes with others
* Don't forget to give admin permissions to the bot

## Troubleshooting

**Bot not responding after activation:**

* Ensure the bot has admin permissions
* Check if Topic ID is correct (if used)
* Make sure the group doesn't restrict bots

**Bot messages not appearing in the correct topic:**

* Double-check the Topic ID
* Ensure the topic is still active
* Try leaving Topic ID empty to send to main chat

**Error when generating activation code:**

* Make sure you have a Zentry NFT
* Refresh the page and try again
* Contact support if the problem persists

## Complete Configuration Examples

### Token Tracker Bot:

```
Token Currency: USD
Token Issuer: rN7n7otQDd6FczFgLdSqtcsAUxDkw6fzRH
Chart URL: https://dexscreener.com/xrpl/sologenic
Trade URL: https://sologenic.org/trade
Website URL: https://sologenic.org
Topic ID: 915
Buy Media URL: https://example.com/buy.gif
Sell Media URL: https://example.com/sell.gif
```

### NFT Tracker Bot:

```
NFT Issuer: rN7n7otQDd6FczFgLdSqtcsAUxDkw6fzRH
NFT Taxon: 12345
Collection URL: https://xrp.cafe/collection/xpunks
Topic ID: 915
```

***

**Need help?** Contact support through:

* Discord: [ZentryBot Discord](https://discord.com/invite/gMQdtmYk3X)
* Telegram: [ZentryBot Community](https://t.me/zentrybotz)
* Website: [zentrybot.xyz](https://zentrybot.xyz)
