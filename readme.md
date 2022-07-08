## R1
#### Purpose
The purpose of this web application is to enable users to order online using their smartphone or whatever device they are using. The end user will have an option of paying using their credit card. Since covid 19 our society has become more online oriented, there is now a more need for an online ordering system like the one we are creating.

Furthermore, this app will support admin functions. The store owner or admin staff can use this app to create, update, delete or edit their menu. Nowadays people like to see what they are ordering first, so this app supports image uploads. As an admin, you can also view the order history, print out receipts and more. 

#### Functionality / features
- View the menu
    - Menu separated by categories (Food, Drinks)
    - View more information on menu item
        - Add menu item to the shopping cart
- Add menu item to the shopping cart
    - User can adjust sugar level, type of milk, quantity


- View shopping cart
    -   Remove items
    -   Edit menu items
- Creating the order
    - Clients info( name , number, email, time to pick up?)
- Make and confirm payment
    - View the order back to the user
        - Order ID
        - Time to pick up
        - View the list of ordered items
- Create Order for Admin to view
    - Receipt gets printed automatically
- Send user receipt via email

#### Target audience
- Restaurant owners
- Any store who wants an online ordering system
- Customers who want to order their food or drinks online 

#### Tech stack
- Payment system (Stripe API)
- User authentication (PassportJs)
- Roles (admins, editors)
    - Admin can create, edit and delete items
    - Editors can only edit menu items
- Authorisation 
- Email (NodeMailer)
- CSS Framework (Tailwind CSS)
- Image Uploads (Cloudinary)
- Deployment
    - Front-End: Netlify
    - Back-end: Heroku
    - Database: Mongo Atlas


## R4 User stories
### Store owner
- As a store owner, I want to see an order list of all orders coming in so I can prepare my order accordingly.
- As a store owner I want to login to my admin with a username and password so that I can securely update my menus and etc
- As a store owner I want to have access to a forgot password feature so that I can recover my password in case I forgot
- As a store owner I want to edit my home page so that my customers can feel welcome when they visit my website and get some details about our store like opening hours
- As a store owner I want to have a about us page so that I can provide some contact information for customers
- As a store owner I want to create new menu items and upload pictures associated with them so that my customers can see what we offer and help them decide what to order
- As a store owner I want to select a category for my menu items so that my this information can help my customers to narrow down their selection
- As a store owner I want to update existing menu items so that I keep the menu up to date
- As a store owners, I want to delete existing menu items so that I can keep up to date with what my customers want
- As a store owners, I want to view my current menus so that I can see what we offer and how they are laid out on the website
- As a store owner, I want to view a history of all orders so that I can keep a record for tax time
- As a store owner, I want to be able to print receipts so that I can use them to assist a customer


### End user
- As a user, I want to order items using my smartphone, tablet or pc so that my order will be ready as soon as I go to the store
- As a user, I want to view all menu items before ordering so that it can help me decide which menu item I want
- As a user, I want to select menu items based on their category so that it can help me narrow down menu item based on their category
- As a user, I want to add a item to a shopping cart so that I don’t forget what I already ordered
- As a user, I want to view my shopping cart at anytime so that I can see what I have already ordered
- As a user I want to edit my menu items from the cart so that in case I change my mind I can still edit it.
- As a user I want to delete an existing item from the cart so that if I decide I don’t want a particular item I can still delete it
- As a user I want to view an existing item from the cart so that I can see the details of what I ordered in case I forgot
- As a user, I want to pay online using a credit card so that I don’t have to use cash.
- As a user I want a confirmation page or email to show everything I ordered and their details so that I can show them to the store owner when I pick them up.
