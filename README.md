# Wikipedia Fill-in-the-blanks game

Wikipedia Fill-in-the-blanks game is an iOS game developed to test the various features that the platform provides.

###### About the Game

The game is simple. A user is displayed content from a random Wikipedia page. 10 words are removed from the content to create blanks. The user needs to fill in these blanks using a jumbled list of words that were removed. He/she gets a score out of 10, depending on the number of blanks that were correctly filled.


### Game Information
When the user opens the app, it displays the text from a random Wikipedia page. (You’re free to use any logic for grabbing text from a random Wiki page) The game requires a minimum of 10 lines of text on the screen. However, we want to show complete paragraphs of text to make it easier to understand the content displayed. Use the least number of paragraphs required to cross the 10 sentence limit.

Once you have the content for the game, proceed to remove words from the text to create 10 blanks. (Each sentence can have at most one blank) Once the blanks are ready, we’re ready to begin the game! Display the complete text to the user, with clearly visible blanks (preferably not just white space) at the appropriate places.

When the user taps / clicks on a blank, a list of all the 10 words are shown (shuffled, of course!) and the user can choose one of them. The UI updates to show that the user has filled up that blank. The user can tap / click a submit button once he’s done and the app shows him his score out of 10. If the user does not fill any particular blank, then he does not get points for it. Along with the user score, a button to “Replay” the game is displayed. Upon tapping / clicking it, the game begins again with another random Wikipedia page.

### Code Part

The game makes use of the following ideas, implemented in Swift 4.2, and xCode10.2 - 
* [URLSession] - To call RESTful API to fetch data from Wikipedia
* [Arc4Random] - To generate a random number to select random words
* [UIButtons] - These buttons are placed over the randomly chosen words so that when the user taps one of them, the system knows where to replace which words.
* [textView text positioning] - These lines of code help us to determine the location of the randomly selected words so that we could place the invisible button over them.
* [UIPickerView] - This is used to display the hidden words to the user so that the user can select on of them for each location.
* [UITableView] - This table is used to show the user their score card along with their choices against the correct answers.

##### Installation
Simply clone or download the project and open it in Swift 4.2, and xCode10.2 to run the application.


# Wikipedia-Game
