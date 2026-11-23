# CoinWatch

## Table of Contents

1. [App Overview](#App-Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## App Overview

### Description

CoinWatch is an Android app for tracking cryptocurrency prices. Users browse a live list of top coins, search by name, open a detail screen with a price chart, and long-press to pin favorites.

### App Evaluation

- **Category:** Finance
- **Mobile:** Quick price checks on the go; list and favorites are built for one-handed phone use.
- **Story:** A clean, simple crypto tracker without the clutter of trading apps.
- **Market:** Casual and hobby crypto investors.
- **Habit:** Checked multiple times a day as prices change.
- **Scope:** Core features fit in 2 weeks; alerts and a portfolio tracker are stretch goals.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- User can view a scrolling list of top cryptocurrencies with icon, name, price and 24h % change
- User can search for a coin by name or symbol
- User can tap a coin to see its detail screen (price chart, market cap, volume, description)
- User can long-press a coin to pin/unpin it as a favorite
- User can pull to refresh prices
- App uses consistent custom styling (dark theme; green for gains, red for losses)

**Optional Nice-to-have Stories**

- User can set price alerts
- User can enter holdings to see total portfolio value
- User can switch chart range (24h / 7d / 30d / 1y)
- User can change display currency

### 2. Screen Archetypes

- **Home / Coin List Screen** (RecyclerView)
  - View list of top coins
  - Pinned favorites appear at the top
  - Pull to refresh
  - Long-press to pin a favorite
- **Search Screen** (or search bar on Home)
  - Type a coin name and see matching results
- **Coin Detail Screen**
  - Price chart, stats, description
  - Favorite (star) button

### 3. Navigation

**Tab Navigation** (Tab to Screen)

- Home (all coins)
- Favorites
- Search

**Flow Navigation** (Screen to Screen)

- Home Screen
  - => Coin Detail Screen (tap a coin)
- Search Screen
  - => Coin Detail Screen (tap a result)
- Coin Detail Screen
  - => Back to previous screen

### 4. API

- **CoinGecko API** (free, no key required): https://www.coingecko.com/en/api
  - `GET /coins/markets?vs_currency=usd`: coin list with prices
  - `GET /search?query={text}`: search coins
  - `GET /coins/{id}`: coin details
  - `GET /coins/{id}/market_chart?vs_currency=usd&days=7`: price history for chart

## Wireframes

[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype
