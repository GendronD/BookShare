# BookShare
BookShare - An app to find users in your area to buy, trade, or sell books!

Looking for a new book, but have a full shelf you don't read anymore? BookShare may be for you! BookShare is designed to bring users together by creating connections based on the books they own or want! Here's how it works, a user's profile will store the user's location and a collection of books - these books could be owned by that user or books they wish to own.  When they create this list, queries will automatically be executed to determine if other users match the parameters set.  This will be determined by the user's location, how far they wish to search for each book, and how they wish to interact with other users (buying, trading, or selling).  If matches are made, a list will be generated for the user to choose a potential match.  It will then be up to the user to contact and perform the exchange.

# Current State:
BookShare currently has a working user authentication system running.  The next step is to build the database in relation to the user.  This will include setting up a database of books for users to access using the GoodReads API.  Once this connection can be made, a form will be created to allow a signed in user to pick a book and save their list of books.  Once users are able to have saved lists of books, implementation of the matching feature will be created.

*In my Introduction to Databases course, I built a basic CRUD version of the BookShare idea.  However, it is designed for SQL.  My goal is to take the necessary portions of that database and port them over to mongoDB.  If you are interested in the other version of that toy site, it is saved in the repository BookShare340.
