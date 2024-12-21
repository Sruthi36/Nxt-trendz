In this project, let's build a **Nxt Trendz**.

### Design Files

<details>
<summary>Click to view</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-sm-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-lg-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>


The app have the following functionalities

- When an unauthenticated user tries to access the **Cart** Route, then the page should be navigated to **Login** Route

- Following are the features to be implemented

  - Feature 1

    - When an authenticated user tries to add the same product multiple times
      - The quantity of the product should be updated accordingly, and the count of the cart items in the header should be remained same

  - Feature 2

    - The total amount and number of items in the cart should be displayed in the **Cart** Route

  - Feature 3

    - In each cart item in the cart
      - When the plus icon is clicked, then the quantity of the product should be incremented by one
      - When the minus icon is clicked, then the quantity of the product should be decremented by one
      - When the quantity of the product is one and the minus icon is clicked, then the respective product should be removed from the cart
      - Based on the quantity of the product, the product price and the Cart Summary, i.e the total cost should be updated accordingly

  - Feature 4

    - When an authenticated user clicks on the remove button, cart item should be removed from the cart list

  - Feature 5

    - When an authenticated user clicks on the **Remove All** button, all the cart items should be removed from the cart and [Empty Cart View](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-empty-cart-view.png) should be displayed

- The `CartContext` has an object as a value with the following properties
  - `cartList` - this key stores the cart items
  - `removeAllCartItems` - this method is used to remove all the cart items in the `cartList`
  - `addCartItem` - this method adds the cart item to the `cartList`
  - `removeCartItem` - this method removes the cart item from the `cartList`
  - `incrementCartItemQuantity` - this method increases the quantity of a product in the `cartList`
  - `decrementCartItemQuantity` - this method decreases the quantity of a product in the `cartList`

</details>

- Prime User credentials

  ```text
   username: rahul
   password: rahul@2021
  ```

- Non-Prime User credentials

  ```text
   username: raja
   password: raja@2021
  ```

</details>

### Resources

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #0b69ff; width: 150px; padding: 10px; color: white">Hex: #0b69ff</div>
<div style="background-color: #171f46; width: 150px; padding: 10px; color: white">Hex: #171f46</div>
<div style="background-color: #616e7c; width: 150px; padding: 10px; color: white">Hex: #616e7c</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>

</details>

<details>
<summary>Font-families</summary>

- Roboto

</details>
