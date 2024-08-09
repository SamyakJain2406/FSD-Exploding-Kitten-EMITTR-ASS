# FSD-Exploding-Kitten-EMITTR-ASS
 This will be an online single-player card game that consists of 4 different types of cards  - Cat card 😼 - Defuse card 🙅‍♂️ - Shuffle card 🔀 - Exploding kitten card 💣
 # 😸 Exploding Kitten

👋 Welcome! The objective of this exercise is to build a web-based game. 

This will be an online single-player card game that consists of 4 different types of cards

- Cat card 😼
- Defuse card 🙅‍♂️
- Shuffle card 🔀
- Exploding kitten card 💣

There will be a button to start the game. When the game is started there will be a deck of 5 cards ordered randomly. Each time user clicks on the deck a card is revealed and that card is removed from the deck. A player wins the game once he draws all 5 cards from the deck and there is no card left to draw. 

Rules –
- If the card drawn from the deck is a cat card, then the card is removed from the deck.
- If the card is exploding kitten (bomb) then the player loses the game.
- If the card is a defusing card, then the card is removed from the deck. This card can be used to defuse one bomb that may come in subsequent cards drawn from the deck.
- If the card is a shuffle card, then the game is restarted and the deck is filled with 5 cards again.

Now create a **react** app using redux which allows a player to draw a random card from the deck once the game is started.

Allow users to create a username to enter the game and create a leaderboard to record how many games they won

You need to use **Redis** as a database to store the points of all the users and **Golang** for the backend. One game won is equal to one point. (Although programming language doesn’t matter in real world but for this exercise please use Golang only)

**Bonus -**

1. Automatically save the game for a user at every stage so the user can continue from where he left off last time.
2. Real-time update of points on the leaderboard for all the users if they are playing simultaneously. 

**Submission Instructions -** 

Please follow these steps for submitting your assignment:

1. **GitHub Code:
-** Upload your full code (both Frontend and Backend) on one GitHub repo.
- Make sure your GitHub link is working and the code is properly organized.

2. **Application Hosting:
-** Your app should be live and working. It helps in the evaluation side for us to see the app live in action
- Share the live URL with us.

3. **README File:
-** Include a README file in your GitHub repo.
- This should have instructions on how to set up and run your app.


## **Technologies Used**
- Backend: Node.js && Express.js
- Frontend: React.js
- Database: SQLITE3

## **Setup Instructions**
- Clone the repository from GitHub: git clone https://github.com/SamyakJain2406/FSD-Exploding-Kitten-EMITTR-ASS
- Navigate to the project directory: cd ExplodingKittens
- Install dependencies:
- Backend: cd backend && npm install
- Client: cd frontend && npm install
- Run the frontend server: npm start
- Run the backend server: npm run server

