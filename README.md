# MIT Shopping Cart - Build Restocking Functionality:

## I. Description:

This web application simulates an online shopping cart, and is built using React as its front-end framework and makes use of state management. The application provides a list of products, each accompanied by an "Add to Cart" button. When users select the button, the corresponding item is added to the shopping cart. Additionally, there is a "Restock Products" button, which, when clicked, retrieves items from the shopping cart and places them back into the stock.

To handle data persistence and communication with the backend, the application makes API calls to a Strapi-powered backend database. The API calls enable retrieving product data, updating stock quantities, and managing the shopping cart state.

By utilizing React's component-based architecture and state management capabilities, the application ensures efficient rendering and updates of the shopping cart. The combination of React, state management, and API calls to the Strapi backend database facilitates the online shopping cart simulation.

## II. Future Additions:

Currently, the web application just shows the restock feature of the shopping cart. But there is a lot of room for improvement which are the following planned future additions:

* Enhance feature of removing items form the cart.
* Display items once in Checkout and just update the quantity.
* Improve the overall user interface. 

##  III. Learning Outcome Addressed:

5. Integrate **Strapi** with a **React application**

In the **shopping cart exercise**, you’ve seen how you can **add** and **remove products** from your **shopping cart**. To **refactor the program**, another feature you can add to your application is **resetting the stock**. In this exercise, you’ll focus on building that **restocking functionality**. To accomplish this, you’ll need to **make a call** to a **Strapi API** and get a **fresh list** of **available products**.

Here’s how the **reset stock feature** works:

* There’s an **input field** on the page that contains the **URL** to the **Strapi back end**
* When a **user clicks** the `“ReStock Products”` button, a **call is made** to the **Strapi back end** specified in the **input field**
* The **result of this call** is an **updated list of products**

Your task is to **implement** the **restock feature**. You should **add your code** to the `“cart.jsx”` file. More specifically, you **need to implement** the `“restockProducts”` function on line `number 169` of **the file**.

[Download these files](/). to get started.

### Hints:

* Make use of the `“doFetch” `function to **make a call** to the **API**.
* Make use of `“setItems”` to **update** the **existing items**.

## IV. Submission Instructions:

When you’re done, **push your work** to a **GitHub repository** titled `Shopping Cart` and **upload the link** to your `“cart.jsx.”` file.

On the **next page**, you’ll **share a short video** showing how the **restocking feature** works in action.

## V. Application Screenshots:

Backend Strapi Database

![Screen_Shots_01.png](Screen_Shots%2FScreen_Shots_01.png)

Console Output while adding items to the cart.

![Screen_Shots_02.png](Screen_Shots%2FScreen_Shots_02.png)

Web Page Rendering and adding items to the shopping Cart.

![Screen_Shots_03.png](Screen_Shots%2FScreen_Shots_03.png)

## VI. License:

MIT License

Copyright (c) 2020 John Williams

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
