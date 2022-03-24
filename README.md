Supermarket Checkout Simulation Project
=============

Supermarket checkout simulation aims to replicate a physical supermarket checkout, through the use of interactive JavaFX menus.

Functionality
-------
My design is based around simplicity, like a branch on a tree it gets more detailed as you open each feature. For example, instead of having separate checkouts for cash, card and point card payments, I decided to integrate it all into one singular modular checkout. The checkout still offers all the flexibility of three separate checkouts, as it provides the user the payment options once they have finished scanning their items. This way the program has less clutter and makes more sense. 
The program functions in a specific order, first, the end-user starts the program and they are greeted with the main menu, they are able to select from 5 different options (Start Checkout, View Checkouts, Save Log, Load Log, Exit)
If the end-user clicks start checkout, a new window will open with a checkout, in this checkout there is a catalogue of 10 unique items that can be scanned via their unique product code, once an item is scanned via its product code it is added to a basket. Items in the basket can also be removed. 
When the end-user wants to pay they can choose from 3 different options. Pay by Cash, which has the user insert coins/notes into the system, Pay by Card, which has the user scan their card and enter the card CVC to pay and Pay by Point Card which has the user enter a valid code to pay for their checkout. 
All checkouts are saved to the program when it is running and these checkouts can be viewed in the main menu “View Checkouts” button. These checkouts can also be saved to a file using “Save Log”, and loaded back into the program using “Load log”.


Required Software
-------
Java SDK 11.0.14
Open JavaFX 11.0.2


VM Options
-------
--module-path "C:/Program Files/Java/javafx-sdk-11.0.2/lib" --add-modules=javafx.controls,javafx.fxml --add-exports javafx.base/com.sun.javafx.collections=ALL-UNNAMED