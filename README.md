# Advanced API Development - JAVA EE Assignment

## Backend of the LA-FIESTA Web POS System

Read this document for a better understand how this system works ! 


This repository contains the front-end code for the Java EE LA_FIESTA POS (Point of Sale) system. The front end is built using HTML, CSS, and JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
##API Documentation https://docs.google.com/document/d/1pCy9JENgrz7FquH7vtZExFBNYLAfRGaBgPlVv6aNTmE/edit?usp=sharing

The Java EE POS System is a web-based point-of-sale system designed for small to medium-sized businesses. This system helps manage sales, inventory, and customer information efficiently.


## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery
- **Backend:** Java EE, Tomcat
- **API Tested:** Postman



## Overview
LA-FIESTA POS System is a web-based Point of Sale (POS) application developed to handle basic operations such as adding, searching, updating, and deleting records. The frontend is built using HTML, CSS, JavaScript, and jQuery, while the backend is powered by Java EE with Tomcat.

## Features
### Customer Management:
- **Add new customers**
- **Search existing customers**
- **Update customer information**
- **Delete customers**

### Item Management:
- **Add new items to inventory**
- **Search existing items**
- **Update item information**
- **Delete items from inventory**

### Order Management:
- **Create new orders**
- **Retrieve and view existing orders**

## Controllers and Endpoints

### Customer Controller
- **Add Customer:** `POST /customer` - Adds a new customer.
- **Search Customer:** `GET /customer/{id}` - Retrieves customer details by ID.
- **Update Customer:** `PUT /customer` - Updates the details of an existing customer.
- **Delete Customer:** `DELETE /customer/{id}` - Deletes a customer by ID.
- **Get Customers:** `GET /customer` - Retrieves a list of all customers.

### Item Controller
- **Add Item:** `POST /item` - Adds a new item to the inventory.
- **Search Item:** `GET /item/{id}` - Retrieves item details by ID.
- **Update Item:** `PUT /item` - Updates the details of an existing item.
- **Delete Item:** `DELETE /item/{id}` - Deletes an item by ID.
- **Get Items:** `GET /item` - Retrieves a list of all items.

### Order Controller
- **Add Order:** `POST /order` - Creates a new order.
- **Get Orders:** `GET /order` - Retrieves a list of all orders.

## Getting Started
1. **Prerequisites:** Ensure you have a Java EE environment set up with Tomcat installed.
2. **Clone the Repository:** `git clone https://github.com/ChathuminiBandara/Lafiesta-Backend`
3. **Setup Database:** Configure your database settings in `application.properties`.
4. **Build and Run:** Deploy the WAR file to Tomcat and access the application.


## License
This project is licensed under the [MIT License](LICENSE).


1. **Clone the repository:**

   ```bash
   gh repo clone ChathuminiBandara/Lafiesta-Backend
