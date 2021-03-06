# ElectroCard


## Project Proposal – Morning Project Group 2
#### Members: Collin, Dustin, Michael, Orion


### Problem to Address:
When working for a business, you want to be able to share your information to potential customers or future employees/employers. The most common way this is done is through business cards. In order to do this, you have to make your cards look professional, and have them printed off. Even then, you have to always keep some cards on hand. In order to make this process quicker and more efficient, our app idea is a digital business card. The app will be able to create your own business card, and allow you to share it with others, as well as save their business card information.

### Activity - Login
Login page allowing access to your cards and saved cards
- Completed (register also included)

### Activity - Main
Basic menu displaying some user information such as your name and allowing you to view/share your card and view other’s saved cards.
- Completed

### Activity - View Cards
Allows you to view created business cards and edit them or create new ones. From this view, you can also select to edit any of your cards. You will also have the option to share your cards, which will give you an ID for the card others input to save that card.
- Complete (Limited Functionality with Edit, Insert and Delete)

### Activity - Add a new Card
Allows you to create and add a new card.
- Complete (Works DB side but view doesn't update)

### Activity - Edit Your Card
Card customization. Color customization, decide content displayed such as name, email, phone number, occupation, workplace, photos etc.
- Complete (Works fully. Due to attempted fixes of insert and delete, edit is not currently functional)

### Activity - Viewing Saved Cards
Here, you will be able to add new cards to save or view all cards that you have previously saved. You will also have the option to remove saved cards if need be. There will be a search/filter capabilities
- Complete (Limited Functionality)

### Activity - Add/Preview new cards
Preview new cards you want to add from other users. Once an id is entered a preview will be shown and you will be given the option to save the card. 
- Complete (Limited Functionality)

### Risky Components:
Implementing a database to store all cards and user information, working with LinkedIn API to gather user information, Card customization as far as coloring, component movement and templates for different amounts of information displayed.

### Test Credentials
The app has 2 users by default.
* username: testuser, password: pass123, userid: 1
    * Note: When logging in and viewing cards with testuser, you should see 3 cards. If not, in the CardModel.java, uncomment the threadPlaceholderCards(); at the top of the CardModel constructor and it should populate cards on next launch.
* username: admin, password: pass, userid: 2

## Current Issues
* App crashes on insert and delete of user cards
* App does not display if new cards have been added or saved
* Saved cards not fully functional
* No icons

### APK
Not included as the app is not finished.