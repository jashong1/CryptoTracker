# Milestone 1 - CoinWatch (Unit 8)

## Table of Contents

1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview

### Description

CoinWatch is a simple cryptocurrency tracker for Android. Users can browse a live list of the top cryptocurrencies, search for a coin, tap a coin to see its price chart and details, and long-press to pin favorites to the top of their list.

### App Evaluation

- **Category:** Finance
- **Mobile:** Users check prices on the go, and a quick-glance list with pinned favorites works best on a phone.
- **Story:** Lets casual investors and curious users track the coins they care about without a cluttered trading app.
- **Market:** Anyone interested in crypto, from beginners to hobby investors.
- **Habit:** Users open the app several times a day to check prices and how their favorites are moving.
- **Scope:** A V1 with the list, search, detail screen and favorites is buildable in 2 weeks. Price alerts and a portfolio tracker are stretch goals.

## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- [ ] **View a list of the top cryptocurrencies with live price and 24h % change**
- [ ] **Search for a coin by name or symbol**
- [ ] **Tap a coin to view a detail screen with a price chart and stats**
- [ ] **Long-press a coin to pin/unpin it as a favorite**
- [ ] **Pull to refresh prices**
- [ ] **Consistent custom styling (dark theme, green/red price colors)**

Stretch Features:

- [ ] Price alerts when a coin moves above/below a target
- [ ] Portfolio tracker (enter how much you own, see total value)
- [ ] Switch chart range (24h / 7d / 30d / 1y)
- [ ] Switch display currency (USD, EUR, etc.)

### 2. Chosen API(s)

- **CoinGecko API** (https://www.coingecko.com/en/api)
  - `GET /coins/markets`: coin list with price, 24h change, market cap and icon (home list, favorites)
  - `GET /search`: search coins by name or symbol (search)
  - `GET /coins/{id}`: coin description and stats (detail screen)
  - `GET /coins/{id}/market_chart`: price history (detail chart)

### 3. User Interaction

Required Feature

- **View coin list**
  - => User scrolls the RecyclerView of coins on the home screen
- **Search**
  - => User types in the search bar (text entry), and the list filters to matching coins
- **View coin details**
  - => User taps a coin (click), and the app navigates to the detail screen
- **Pin favorite**
  - => User long-presses a coin (long click), and it is pinned to the top with a star icon
- **Refresh**
  - => User pulls down on the list, and prices reload from the API

## Wireframes

<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

<br>

# Milestone 2 - Build Sprint 1 (Unit 9)

## GitHub Project board

[Add screenshot of your Project Board with three milestones visible in
this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Issue cards

- [Add screenshot of your Project Board with the issues that you've been working on for this unit's milestone] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>
- [Add screenshot of your Project Board with the issues that you're working on in the **NEXT sprint**. It should include issues for next unit] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Issues worked on this sprint

- List the issues you completed this sprint
- [Add giphy that shows current build progress for Milestone 2. Note: We will be looking for progression of work between Milestone 2 and 3. Make sure your giphys are not duplicated and clearly show the change from Sprint 1 to 2.]

<br>

# Milestone 3 - Build Sprint 2 (Unit 10)

## GitHub Project board

[Add screenshot of your Project Board with the updated status of issues for Milestone 3. Note that these should include the updated issues you worked on for this sprint and not be a duplicate of Milestone 2 Project board.] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Completed user stories

- List the completed user stories from this unit
- List any pending user stories / any user stories you decided to cut
from the original requirements

[Add video/gif of your current application that shows build progress]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## App Demo Video

- Embed the YouTube/Vimeo link of your Completed Demo Day prep video
