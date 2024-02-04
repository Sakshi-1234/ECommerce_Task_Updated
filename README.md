# Ecommerce (React) Coding Assessment

## Overview

To complete this assessment, you will need to use this [Ecommerce-boilerplate](https://github.com/gurukishore111/Ecommerce-boilerplate) web app.

The purpose of this assessment is to assess your **skills and approach to composing a simple web app** given an API feed.

## What to do?

Your goal is to implement an eCommerce application. The CSS framework/library is totally up to you.

Although it's a very basic exercise, we will be looking for simple, well-designed, well-commented, and tested code in the submission.

Please include a `README` with setup instructions and any other documentation you created as part of your solution.

Also, add very short info for the following to your `README`:

- Describe all the application functionalities
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

Once you complete implementation, please add the link to the hosted repository (e.g. Github). Alternatively, you may submit your code as a ZIP file too.

(NOTE: You have to use the latest version of v18 and react-router-dom v6)

## How should the application work?

The user of this react application should be able to view all the products. The application should have the following workflow,

1. Create the login/register functionality.
2. Once the user is authenticated
3. Users can add the products to the cart page
4. Also user can add their favourite products

## Development Setup

- Clone this repo
- `npm install` - To install the dependencies
- `npm run server` - To start the JSON server
- `npm start` - To start the react app

## This project's user interface should like this.

### Login/Register page
![image](https://github.com/Sakshi-1234/ECommerce_Task_Updated/assets/77981502/d13ae334-7cfa-468d-bc5e-5dac9bccc8f2)


### Home page

![image](https://github.com/Sakshi-1234/ECommerce_Task_Updated/assets/77981502/d8d08aaf-36ab-46b8-a9aa-620b6366b162)



### Cart page

![image](https://github.com/Sakshi-1234/ECommerce_Task_Updated/assets/77981502/3e7a4ad1-b6cb-4fcd-b88e-0b9a7bc53ea0)


## API Usage

API can be launched using npm run server.
| Endpoint | Result |
|------------------------------|-----------------------------------------------------|
| /users | Lists all available users |
| /products | Lists all available products |
| /orders | Lists all available orders  
| /favourites | Lists all available favourites

Refer - [JSON sever](https://www.npmjs.com/package/json-server) docs for more information

## Bonus

- Feel free to add functionality (not mandatory)
- Use redux/context for state management
- Well explained readme (screenshot etc)

---
