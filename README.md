# Deck Battle Arena 🃏

DeckBattle Arena is a real-time multiplayer card game application that allows up to 4 players to compete using a standard deck of 52 cards. The game features action cards with special abilities such as skipping turns, reversing play order, and drawing extra cards.

## Features

- **Real-time Gameplay:** Utilizes Socket.io for real-time communication between players.
- **Player Interaction:** Players can join or create games and take turns playing cards.
- **Action Cards:** Special cards (Aces, Kings, Queens, Jacks) trigger unique game effects.
- **Responsive Design:** Built with React-Bootstrap for a responsive and intuitive user interface.

## Technologies Used

- **Next.js**: Framework for server-side rendering and static site generation.
- **Socket.io**: Enables real-time, bidirectional communication between clients and server.
- **Express**: Web framework for building the server-side logic.
- **MongoDB**: NoSQL database for storing game state and user data.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **React-Bootstrap**: Provides Bootstrap components as React components for styling.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Hritvik-Mohan/deck-battle-arena
   cd deck-battle-arena
2. **Install dependencies:**

    ```bash
    npm install
3.  **Set up environment variables:**

- Create a .env file in the root directory and add the necessary environment variables. Example:

    ```bash
    MONGO_URI=<mongodb_connection_string>
4. **Run the development server:**

    ```bash
    npm start
## Usage

- **Create a Game:** Navigate to the game creation page to start a new game.
- **Join a Game:** Enter a game ID to join an existing game.
- **Play the Game:** Follow the on-screen instructions to play your cards and interact with other players.