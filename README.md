# [MEMORY GAME](https://guavalines.github.io/Memory_Game/)

# Description
cardArray is an array containing objects with the name and image source of each card. It's randomized using the sort method and a random number generator.

The createBoard function appends img elements to the div with ID grid, creating a grid of cards with a blank image and a unique data-id attribute.

The flipCard function gets the card's data-id attribute and retrieves the corresponding name and img properties from cardArray. It sets the card's image to the img property and adds the name to an array cardsChosen.

The checkMatch function checks whether the two cards have the same name, updates their images accordingly, and keeps track of the user's score in the cardsWon array. If all cards have been matched, the user is alerted that they have won.

The score (i.e., how many pairs of cards have been matched) is displayed on the HTML page in the span with ID result.

# Tools

![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
