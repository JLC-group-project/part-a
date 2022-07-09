## R1

#### Purpose
The purpose of this web application is to enable end-users to order online on their desktops or smart devices and allow them to make purchases with an online payment system. Due to Covid-19, society has adapted our day-to-day activities to be more online-oriented, and therefore there is a bigger emphasis on web applications to have an online ordering system. 
 
This app gives store owners administrative functionality to create, edit, or delete menu items for their menu. Furthermore, they can also view the current orders, the history of all orders and print receipts. Customers usually would like to see what their product would look like before ordering and therefore this app also supports image uploading.


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
- MERN Stack
    - Front-End
        - ReactJS
        - CSS Framework (Tailwind CSS)
 
    - Back-End
        - ExpressJS
        - NodeJS
- Database
    - MongoDB
- NPM Libraries
    - User authentication (PassportJs)
    - JSON Web Token
    - Email (NodeMailer)
- API
    - Payment system (Stripe API)
    - Image Uploads (Cloudinary)
- Deployment
    - Front-End: Netlify
    - Back-end: Heroku
    - Database: Mongo Atlas


## R2 Dataflow Diagram

### Admin Login
![Data Flow Diagram for Admin Logins](/src/DataFlow_Login.jpg)

### Admin Functionality
![Data Flow Diagram for Admin Functionality](/src/DataFlow_Admin.jpg)

### User Functionality
![Data Flow Diagram for User Functionality](/src/DataFlow_User.jpg)

## R3 Application Architecture Diagram

![Application Architecture Diagram](/src/Application-Architecture-Diagram.jpg)


## R4 User stories
### Store owner
#### View orders:
- As a store owner I want to see an order list of all orders coming in so I can prepare my order accordingly.
#### Login:
- As a store owner I want to login to my admin with a username and password so that I can securely update my menus and etc
- As a store owner I want to have access to a forgot password feature so that I can recover my password in case I forgot

#### Edit home and about us page:
- As a store owner I want to edit my home page so that my customers can feel welcome when they visit my website and get some details about our store like opening hours
- As a store owner I want to have a about us page so that I can provide some contact information for customers
- As a store owner I want to create new menu items and upload pictures associated with them so that my customers can see what we offer and help them decide what to order

#### Create new menu items:
- As a store owner I want to select a category for my menu items so that my this information can help my customers to narrow down their selection
- As a store owner I want to update existing menu items so that I keep the menu up to date
- As a store owners, I want to delete existing menu items so that I can keep up to date with what my customers want
- As a store owners, I want to view my current menus so that I can see what we offer and how they are laid out on the website

#### Order history:
- As a store owner, I want to view a history of all orders so that I can keep a record for tax time
- As a store owner, I want to be able to print receipts so that I can use them to assist a customer


### End user
#### Order online:
- As a user, I want to order items using my smartphone, tablet or pc so that my order will be ready as soon as I go to the store
- As a user, I want to view all menu items before ordering so that it can help me decide which menu item I want

#### View orders:
- As a user, I want to select menu items based on their category so that it can help me narrow down menu item based on their category
- As a user, I want to add a item to a shopping cart so that I don’t forget what I already ordered

#### Shopping cart:
- As a user, I want to view my shopping cart at anytime so that I can see what I have already ordered
- As a user I want to edit my menu items from the cart so that in case I change my mind I can still edit it.
- As a user I want to delete an existing item from the cart so that if I decide I don’t want a particular item I can still delete it
- As a user I want to view an existing item from the cart so that I can see the details of what I ordered in case I forgot
- As a user, I want to pay online using a credit card so that I don’t have to use cash.

#### Confirmation email
- As a user I want a confirmation page or email to show everything I ordered and their details so that I can show them to the store owner when I pick them up.

## R5 Wireframe--Created with Figma

#### User Side

**Home Page User**

![HomePageUser](/src/HomePageUser.png)

**Menu User**

![MenuUser](/src/MenuUser.png)

**About Us User**

![AboutUs](/src/AboutUs.png)

**Checkout User**

![CheckOutUser](/src/CheckOutUser.png)

**Payment User**

![PaymentUser](/src/PaymentUser.png)

#### Admin Side

**Sign In admin**

![SignInAdmin](/src/SignInAdmin.png)

**Forget Password Admin**

![ForgetPasswordAdmin](/src/ForgetPasswordAdmin.png)

**Change Password Admin**

![ChangePasswordAdmin](/src/ChangePasswordAdmin.png)

**Home Page Admin**

![HomePageAdmin](/src/HomePageAdmin.png)

**Menu Admin**

![MenuAdmin](/src/MenuAdmin.png)

**About Us Admin**

![AboutUsAdmin](/src/AboutUsAdmin.png)

**Create Edit Menu Admin**

![Create_EditAdmin](/src/Create_EditAdmin.png)

**Orders Admin**!

![OrdersAdmin](/src/OrdersAdmin.png)

**Order History Admin**

![OrderHistoryAdmin](/src/OrderHistoryAdmin.png)



## R6: Trello board

![Trello1](/src/Trello1.png)

![Trello2](/src/Trello2.png)

![Trello3](/src/Trello3.png)

![Trello4](/src/Trello4.png)

![Trello5](/src/Trello5.png)