**Change ShoppingCart Model: Done**

**Empty Shopping Cart: Done**

**Decrease Shopping Item: Done**

**Create OrderDetail: Done**

**Create Order: Done**
- Provide User ID for every page
    - Add `$_SESSION['current_userid']` : Done
- Get the other values of Order
    - upgrade ShoppingCart Components Default View: So it can post values of both Order and items; Done
    - Get all this value post from Shopping Cart Default and show in OrderController->create_POST(); Done

- Insert Order and Item values into DB
    - INSERT a Order model; Done
    - PASS this OrderID to every OrderDetail model and INSERT to DB; Done
- Order index(Action & View)
    - Upgrade Register View (make user input Phone and address info when registering): Done
    - Retrieve order info(phone & address) from users and inject into Order model: Done

**Create OrderDetail: Begin**
- Create MVC for OrderDetail: Working
    - Model->get_all(): Done
    - index View: Get hat info from item record: Done
    - Add Status to Order column and update create() get_all() action: Done
