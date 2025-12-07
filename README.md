# mtg-card-data
This repository contains a complete, up-to-date local export of Magic: The Gathering card data, sourced from the public Scryfall API. The dataset includes one entry per unique MTG card (not re-prints) (oracle card) and is intended for read-only consumption.

cards.json
A JSON array containing ~31,000 unique MTG cards.

Each card object includes:

Card name

Image URL (hosted by Scryfall)

Mana cost

Converted mana cost (CMC)

Card type line

Colors

Rarity

Set name (representative printing)

Data Format
Example entry:
{
  "id": "4e51e7e3-8a8a-4b6a-9cfe-dc7c57491f42",
  "name": "Black Lotus",
  "imageUrl": "https://cards.scryfall.io/normal/front/...",
  "manaCost": "{0}",
  "cmc": 0,
  "typeLine": "Artifact",
  "colors": [],
  "rarity": "rare",
  "set": "Limited Edition Alpha"
}
