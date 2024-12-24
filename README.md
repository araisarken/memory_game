## Memory Game  
This project is a fun and interactive Memory Card Matching Game developed using HTML, CSS, and JavaScript. The game challenges players to test their memory by matching pairs of cards within the least amount of time and moves possible.  
---
### Key Features  
1. Randomized Card Layout: The cards are shuffled at the start of every game for a unique experience.  
2. Card Flip Animation: Smooth animations for flipping cards enhance the user experience.  3. Move Counter: Tracks the number of moves the player has made.  
4. Timer: Records how long the player takes to finish the game.  5. Game Controls: Start and stop the game anytime with interactive buttons.  
6. Responsive Design: Works seamlessly across devices, including desktops, tablets, and smartphones.  
---
### Project Structure  .
├── index.html        # Main HTML file containing the structure of the game├── style.css         # Custom CSS for styling and animations
├── script.js         # JavaScript logic for shuffling, matching, and tracking stats
#### Files Overview  - index.html: Contains the structure of the app, including the game area, start/stop buttons, and stats display.  
- style.css: Defines the layout, colors, and card flip animations.  - script.js: Implements the game logic, such as shuffling cards, tracking time/moves, and handling user interactions.  
---
### Usage  
1. Start the Game:  
   - Click the "Start Game" button. The timer will start, and the cards will appear face-down.  
2. Flip Cards:     - Click on a card to flip it and reveal its image. Try to find its matching pair.  
3. Match Cards:  
   - If two flipped cards match, they remain face-up.     - If they don't match, they will flip back after a brief delay.  
4. Win the Game:  
   - Match all the pairs to win! The timer and move counter will display your results.  
5. Stop the Game:     - Click "Stop Game" to reset the board and stop the timer.  
---

### Technologies Used  
- HTML: Provides the structure of the game.  - CSS: Adds styling, layout, and animations for card flipping.  
- JavaScript: Implements game logic, including randomizing cards, tracking stats, and handling interactions.  
---
### How It Works  
1. Card Setup:     - The items array contains the details of each card (name and image).  
   - The randomize function shuffles the cards to ensure they appear in a random order every time.  
2. Card Flipping:     - Clicking a card triggers the flipCard function, which visually flips the card and checks for matches.  
3. Matching Logic:  
   - If two flipped cards match, they stay face-up.     - If they don't match, they flip back after a short delay using the checkMatch function.  
4. Timer and Moves Counter:  
   - The startTimer function starts counting seconds when the game begins.     - Every time a pair of cards is flipped, the move counter increments.  
---
### Future Enhancements  
1. Add difficulty levels (e.g., more cards for advanced levels).  
2. Include sound effects for card flips and matches.  3. Save the best time and moves in local storage for a leaderboard.  
4. Add themes for cards (e.g., animals, fruits, emojis).  
---
### Author  
- Developed by: Sarken Arailym  
If you have any questions or suggestions, feel free to reach out! 😊
