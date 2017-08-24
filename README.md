# RockPaperScissorsGame
I set up the storyboard and view controller files:

Step 1. Created a new Xcode project using the Single View template.

Step 2. Added a swift file to project, a subclass of UIViewController, inorder to have two view controller files.I gave the view controllers descriptive names.

Step 3. Dragged a second view controller into storyboard and set its class in the identity inspector.

Step 4. Added buttons and labels. 

Step 5. Connected button and label outlets.

Step 6. Randomly generated an opponent’s play i.e. rock, paper, or scissors.
Compared the user’s play with the randomly generated play to determine a winner.
Generated a message for the results of a match, for example: “Paper covers rock. You win!”

Step 7. I presented the results view controller in three different ways.

All code: Instantiate the results view controller using the storyboard, and set the text of its label property. Connect the action on the rock button.

Perform Segue by Identifier: Create a named segue, and invoke the performSegueWithIdentifier method in the paper button action. In this case, the label text should be set in the prepareForSegue method.

Automatically Triggered Segue: Create an automatically triggered segue in storyboard, connected directly to the scissors button. In this case, the label text should also be set in the prepareForSegue method.
Set up the “Play again” button:

Step 8. Wrote a “play again” method that dismisses the results view controller.

Step 9. Connected the action on the play again button.

Step 10. RockPaperScissors App is COMPLETE!
