---
layout: essay
type: essay
title: "Checkpoint assignment 3"
# All dates must be YYYY-MM-DD format!
date: 2023-12-12
published: true
labels:
  - MIS
---

Show what each page will look like. The pages do not have to be “functional” but the design should be clear. Here is an example PPT prototype

click for screencast [here](https://drive.google.com/drive/folders/1PpmERPSFbqceKTdIoGb6ESgl1XppO1i-).

Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.

I will design my shopping cart as from products display it will post to add to the cart. I will have one products.html to display the three different groups. The add to cart will be a separate page where they can add or decrease the quantity and that page will also be the invoice. the difference between an invoice and a cart is that the user would need to be logged in for the invoice and the personalization due to the cookies and for the invoice, the user would not have the option to alter quantities. The changes will be done through window onload functions. 

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, and what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.

The shopping cart data that will be stored in the session would be their add-to-cart data which will be handled on the server in an array. 
{Shoes: [0. 3. 2], Apperal: [1, 0, 5]}

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?

I will use cookies to check if the user has logged in or registered. The user will have access to products and add them to the cart. But to purchase at the cart they will have to be either logged in or redirected to the login/ registration. this validation will be through if statements on the server when clicking the purchase button. The issue with this is securing the data not to be altered by other users. 

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?

I am working alone. 

How are you approaching Assignment 3 differently than Assignment 2?

I am approaching assignment 3 differently than 2 by doing this layout to strategically think about how I will execute it and pre-thinking of the user issues that could come up. I am also going it as a simpler approach than just copy-paste and sift through that mess. 
