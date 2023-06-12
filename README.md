# Module 19.4 - Build Restocking Functionality:

##  Learning Outcome Addressed:

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

## Submission Instructions:

When you’re done, **push your work** to a **GitHub repository** titled `Shopping Cart` and **upload the link** to your `“cart.jsx.”` file.

On the **next page**, you’ll **share a short video** showing how the **restocking feature** works in action.

