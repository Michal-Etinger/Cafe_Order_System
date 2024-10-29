# YAY COFFEE! Project

## Project Overview
The *YAY COFFEE!* project is a web-based application designed to manage a coffee shop's online operations. This platform enables administrators to manage menu items, customers to place orders and submit reviews, and operators to handle orders efficiently.

## Users
The system includes three types of users, each with distinct roles and functionalities:
- *Admin:* Manages menu items and other administrative features.
- *Customer:* Places orders, submits reviews, and uploads photos.
- *Operator:* Views and closes open orders from customers.

## Processes
1. *Login:* All users must log in to access their designated features.
2. *Menu Management (Admin):* Admin users can add new items to the menu, each with a name, description, and price.
3. *Order Placement (Customer):* Customers can place an order by selecting items from the menu and entering their information.
4. *Order Handling (Operator):* Operators can view open orders and mark them as closed once fulfilled.
5. *Review Submission (Customer):* Customers can submit a review, rate their experience, and optionally upload a photo.

## Data Management
The application uses an SQLite database with the following tables:
- *Users*: Stores information on all users, including their username, password, and role.
- *Orders*: Tracks customer orders with details such as customer name, items ordered, and order status.
- *Items*: Manages menu items, including name, description, and price.
- *Reviews*: Stores customer reviews, ratings, and photo paths.

## Architecture
The *YAY COFFEE!* system follows the MVC (Model-View-Controller) architecture:
- *Model*: Handles data management and database interactions using SQLAlchemy.
- *View*: Defines HTML templates that display data and interact with users.
- *Controller*: The Flask app (app.py) routes user requests to the correct functionality and templates.

## Screenshots
### Login screen where users enter credentials to access the system.

![תמונה של WhatsApp‏ 2024-10-29 בשעה 14 15 07_df8cc6c3](https://github.com/user-attachments/assets/bc4fdb3a-4a2b-4e42-8081-3846689732b0)

Admin screen to add new menu items.

![תמונה של WhatsApp‏ 2024-10-29 בשעה 14 16 48_da721072](https://github.com/user-attachments/assets/b8bdddc2-737c-4a97-b715-0a9df4545eb5)


Customer screen to place a new order.

![תמונה של WhatsApp‏ 2024-10-29 בשעה 14 15 43_fe69bc04](https://github.com/user-attachments/assets/87ebdbf7-3b55-47e3-891c-d3961ba0ad8c)

Operator screen to view and close open orders.

![תמונה של WhatsApp‏ 2024-10-29 בשעה 14 17 24_eec2028e](https://github.com/user-attachments/assets/3fc4a01e-4b40-4d68-8af3-7c42d507ac49)


