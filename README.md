# Pokémon Database

A web application that displays a comprehensive database of Pokémon, fetching data from PokeAPI, calculating additional statistics, and providing an interactive user interface with filtering and audio features.

## Features

*   **Extensive Pokémon Data:** Displays a wide range of Pokémon attributes including:
    *   Dex #
    *   Types
    *   Abilities
    *   Base Stats (HP, Attack, Defense, Special Attack, Special Defense, Speed)
    *   Total Stats (sum of base stats)
    *   Product Stats (product of base stats)
    *   Generation
    *   Height
    *   Weight
    *   Grass Knot Power (auto-calculated based on weight)
    *   Egg Group(s)
    *   Gender Ratio
*   **Dynamic Filtering:** Filter Pokémon by all provided specifications.
*   **Interactive Cards:** Each Pokémon is displayed as a card with an image.
*   **Pokémon Cries:** Touching a Pokémon's image plays its latest cry.
*   **Data Sourcing:** All core Pokémon data is sourced from the official [PokeAPI](https://pokeapi.co/).

## Technologies Used

### Backend / Data Processing (Python)

*   **Python 3:** For scripting and potentially serving data.
*   **`requests`:** To make HTTP requests to the PokeAPI.
*   **`sqlite3`:** A lightweight, file-based database for storing processed Pokémon data.
*   **(Optional) Flask/FastAPI:** For creating a simple REST API to serve data to the frontend, especially for advanced filtering.

### Frontend (React)

*   **React.js:** A JavaScript library for building user interfaces.
*   **HTML5/CSS3:** For structuring and styling the web application.
*   **Axios:** For making HTTP requests from the frontend to the backend/API.
*   **Web Audio API:** For playing Pokémon cries.

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Pokemon-Database-Repo.git
cd Pokemon-Database-Repo
