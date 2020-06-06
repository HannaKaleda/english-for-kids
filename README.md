# english-for-kids
**See application demo** - https://hannakaliada-english-for-kids.netlify.app/

The English-for-kids application was created using **HTML, SASS, JS, Webpack**

**Application description**
1. The application works in training mode and in game mode.
2. When you download the application or reload the page, the application opens in training mode.
Switching between training and playing occurs by clicking on the Train / Play switch.
3. When you click on the card, the pronunciation of the word in English sounds.
4. On each card there is a button, when clicked, the card rotates on the back where there is a translation of the word. When the mouse cursor moves beyond the borders of the card, it automatically rotates to the front side.
5. In game mode, the above features of the training mode are disabled, the button, when clicked, the card flips over, and the text on the card is hidden. The "Start game" button appears.
6. After clicking on the "Start game" button, the English pronunciation of the random word from the choosen category sounds.
7. For each page, and for each game, random words are generated in a new way.
8. After the first click on the "Start game" button, the inscription on it changes to the "Repeat" icon, the appearance of the button changes. When you click on the "Repeat" button, the pronunciation of the word sounds again.
9. If the user clicked on the active card with the wrong answer, the sound signal "error" is heard.
10. If the user clicked on the active card with the correct answer, the sound signal "correct" is heard and after it the pronunciation of the random word from those that have not yet sounded.
11. A card with a guessed word becomes inactive, and its appearance changes. Clicks on an inactive card are not accompanied by sound effects, they do not affect the game score.
12. After the start of the game, each click on the active card is the right or wrong answer. These answers are displayed in the form of ticks / crosses of different colors in the rating scale, which appears in the game mode.
13. If there are too many ticks / crosses and the scale is completely filled with them, the previous ones are hidden, and new ones continue to be added.
14. if all words are guessed correctly, the “success” signal sounds, cards with words are hidden, a joyful smiley is displayed on the page.
15. If there were errors when guessing words, the “failure” signal sounds, cards with words are hidden, a sad smiley and the number of mistakes are displayed on the page. the application automatically redirects to the main page with a list of categories.
16. The statistics page contains a list of all categories, all words in each category, and a translation of each word.
17. Statistics are shown next to each word - how many times a card with a given word was clicked in training mode, how many times this word was guessed in game mode, how many mistakes were made, the percentage of correct answers for each word in game mode. After restarting the application, statistics are saved.
18. It is possible to sort the data alphabetically, for numerical values - by their size. Sorting can occur in direct and reverse order.
19. On the statistics page there is a "Reset" button. The "Reset" button resets statistics.

**To run the application, you need to**
1. Install Node.js
2. Clone the repository
3. Go to folder english-for-kids
4. To install all dependencies use `npm install`
5. To run the application use `npm start`

