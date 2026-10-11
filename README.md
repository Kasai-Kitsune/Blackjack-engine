# Blackjack-engine
Simple blackjack game that can be run locally.
- Blackjack pays 3:2
- Dealer stands on all 17s, or hits soft 17 (toggleable in options)
- Insurance with American peek on dealer Ace or 10
- Even money offered on a player blackjack against a dealer Ace
- Double on any first two cards, including after a split
- Split up to 4 hands; split aces receive one card and auto-stand
- Late surrender

## Features

### Multi-Deck Shoe
- Choose 1, 2, 4, 6, or 8 decks
- Persistent shoe mode carries cards across hands, tracks a discard tray, and reshuffles at a 25% cut card
- Single deck without persistence reshuffles every hand (on by default)

### Side Bets
- Perfect Pairs: mixed 6:1, colored 12:1, perfect 25:1
- 21+3: flush 5:1, straight 10:1, three of a kind 30:1, straight flush 40:1, suited trips 100:1
- Each side bet is capped at the main wager

### Hi-Lo Count Trainer
- Running count and true count HUD
- Requires persistent shoe mode
- The dealer's hole card is excluded from the count until it is revealed

### Session Stats
- Hands played, win rate, net result, current streak, and best streak

**Mobile optimized, but keyboard shortcuts are incldued** 

## Keyboard Shortcuts

| Key | Action |
| --- | --- |
| Space | Deal |
| H | Hit |
| S | Stand |
| D | Double |
| P | Split |
| R | Surrender |
| B | Rebet |
| C | Clear bet |
| Y / N | Accept or decline insurance and even money |
