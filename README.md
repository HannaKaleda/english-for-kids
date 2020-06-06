# english-for-kids
**See application demo** - https://hannakaliada-english-for-kids.netlify.app/

The English-for-kids application was created using **HTML, SASS, JS, Webpack**

**Application description**
1. The application works both in training game modes.
2. When you download the application or reload the page, it opens in training mode.
3. Switching between training and playing occurs by clicking on the Train / Play switch.
4. The user will be able to hear words pronunciation in English after clicking on the chosen card.
5. There is a button on each card. The card rotates on the back after clicking it. There is a translation of the word on the backside of each card. After moving the cursor beyond the borders of the card, it automatically rotates to the front side.
6. The above features of the training mode are disabled in the game mode. After clicking on the switch the card flips over, the text on the card is hidden and the "Start game" button appears.
7. The English pronunciation of the random word from the choosen category sounds after clicking on the "Start game" button.
8. Random words are generated in a new way before each page and each new game.
9. The inscription on the "Start button" changes to the "Repeat" icon and the appearance of the button also changes after the first click on the button. The pronunciation of the word sounds again after clicking on the "Repeat" button.
10. If the user clicks on the active card with the wrong answer, the sound signal "error" will appear.
11. If the user clicks on the active card with the correct answer, the sound signal "correct" will appear. In such case the user will hear the pronunciation of the random word that has not sounded before.
12. A card with a guessed word becomes inactive and its appearance changes. Clicks on an inactive card are not accompanied by sound effects and do not affect the game score.
13. Each click on the active card is the right or wrong answer after the start of the game. These answers are displayed in the form of ticks / crosses of different colors in the rating scale, which appears in the game mode.
14. If there are too many ticks / crosses and the scale is completely filled with them the previous ones will be hidden and new ones will continue to be added.
15. If all words are guessed correctly, the “success” signal will sound, cards with words will be hidden, a joyful smiley will be displayed on the page.
16. If there were any errors the “failure” signal will sound, cards with words will be hidden, a sad smiley and the number of the mistakes will be displayed on the page. the application automatically redirects users to the main page with a list of categories after finishing the game.
17. The statistics page contains a list of all categories, all words in each category and their translations.
18. Statistics are shown next to each word - how many times a card with a given word was clicked in training mode, how many times this word was guessed in game mode, how many mistakes were made, the percentage of correct answers for each word in game mode. Statistics are saved after restarting the application.
19. There is a possibillity to sort the data alphabetically and by size for numerical values. Sorting can occur in direct and reverse order.
20. There is a "Reset" button on the statistics page. It resets statistics.

**To run the application, you need to**
1. Install Node.js
2. Clone the repository
3. Go to folder english-for-kids
4. To install all dependencies use `npm install`
5. To run the application use `npm start`

