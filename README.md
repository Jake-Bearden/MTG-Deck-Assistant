# MTG Commander Deck Builder & Analyzer

A Python-based Magic: The Gathering deck-building and analysis tool powered by the [Scryfall REST API](https://scryfall.com/docs/api).

## Overview

Magic: The Gathering (MTG) is a strategic collectible card game in which players construct customized decks from an extensive pool of approximately 30,000 unique cards. Players combine different card types, mechanics, and abilities to develop synergistic strategies and compete against opponents.

This application focuses on the **Commander (EDH)** format, a multiplayer variant utilizing 100-card singleton decks built around a designated Commander. The Commander's color identity determines which cards are legal within the deck.

The goal of this project is to simplify card discovery, automate deck analysis, and eventually incorporate machine learning to assist with deck construction and optimization.

## Features

- **API Integration:** Retrieve structured card data through the Scryfall REST API.
- **Advanced Card Search:** Search by card name, keywords, abilities, colors, and creature subtypes.
- **Commander Compatibility:** Filter cards according to color identity.
- **Price Filtering:** Identify cards within a specified budget.
- **Card Information:** Retrieve mana costs, card types, rules text, and abilities.
- **Deck Analysis (Planned):** Calculate mana curves, color distribution, average mana value, and deck composition.
- **Machine Learning (Future Development):** Explore card synergies and generate Commander-specific deck recommendations.

## Technologies

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| Requests | HTTP requests and API communication |
| Scryfall REST API | Card database and structured data retrieval |
| JSON | API response parsing and data handling |
| Machine Learning | Future card recommendation system |

## API Reference

This project utilizes the Scryfall API to retrieve Magic: The Gathering card information.

Documentation: https://scryfall.com/docs/api

Example endpoint:

```python
https://api.scryfall.com/cards/search
```

Search parameters are passed through HTTP query strings, allowing the application to dynamically retrieve cards based on user-defined criteria.

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate into the project directory:

```bash
cd MTG-Commander-Deck-Builder
```

3. Install dependencies:

```bash
pip install requests
```

4. Run the application:

```bash
python main.py
```

## Development Roadmap

- [x] Establish Python development environment
- [x] Integrate Scryfall REST API
- [x] Implement card search functionality
- [x] Add keyword and color-based filtering
- [x] Retrieve card abilities and rules text
- [ ] Implement Commander deck-list input
- [ ] Develop automated
