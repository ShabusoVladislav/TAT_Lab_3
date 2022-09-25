## **Test-cases**

*Web-site:* [Lyle & Scott ](https://row.lyleandscott.com/)

------

#### 1. Add a Hat to the Basket

**Preconditions:**

- Website [Lyle & Scott ](https://row.lyleandscott.com/) is opened;
- All pop-ups (such as *Accept All Cookies* or *Sign up to newsletter*) are closed;

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | :----------------------------------------------------------- | ------------------------------------------------------------ |
|    1    | Hover over the *Mens* category in the header, select the *Hats & Caps* category | Page with Hats & Caps is opened                              |
|    2    | Click on hat you want to buy                                 | Page with selected hat is opened                             |
|    3    | Click another color of hat (if there are any other colors)   | Another color is highlighted, pictures with a hat of another color are loaded |
|    4    | Choose size of hat (if it possible) and quantity             | Chosen size and quantity are highlighted, button *BUY NOW* is available |
|    5    | Click on the button *BUY NOW*                                | Pop-up *Added to your basket* is opened with info about hat and it's properties, price, quantity and subtotal price of items in the basket. Buttons *VIEW BUSKET* and *CONTINUE SHOPPING* are available. Hat was added to the basket |

------

#### 2. Buy items from the basket

**Preconditions:**

- Website [Lyle & Scott ](https://row.lyleandscott.com/) is opened;
- There is at least one item in the basket.

**Test steps:**

| Step ID | Action                                                       | Expected result                                              |
| :-----: | ------------------------------------------------------------ | ------------------------------------------------------------ |
|    1    | Hover over *MY BAG* in the header                            | Items from the basket and total price are displayed          |
|    2    | Click *MY BAG* button                                        | Basket page is opened, selected items and basket subtotal are displayed |
|    3    | Change quantity of any item in the basket                    | Price of that item and basket subtotal are recalculated      |
|    4    | Click on any of the payment systems                          | *Account Login* page is opened offering to sign in, register or continue as guest |
|    5    | Click on *CONTINUE AS GUEST* button                          | *Checkout* page is opened                                    |
|    6    | Fill the *Email address* text field with *vladshabusov.gmail.com* | Error with message "**Please enter a valid email address.**" is displayed |
|    7    | Fill in **Email and delivery address** fields with correct data | **Delivery Options** selection is available                  |
|    8    | Select delivery option; select payment method or fill in card details and click *Submit My Order* button | Payment confirmation page is opened                          |
|    9    | Click *Pay* button                                           | Order is placed                                              |