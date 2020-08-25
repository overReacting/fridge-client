# Fridge



## Important Links

- [Deployed Client](https://overReacting.github.io/fridge-client/)
- [Client Repo](https://github.com/overReacting/fridge-client)
- [Deployed API](https://somethingsomething.herokuapp.com)
- [API Repo](https://github.com/overReacting/fridge-api)

## Planning Story



### User Stories

- As an unregistered user, I would like to sign up with email and password.
- As a registered user, I would like to sign in with email and password.
- As a signed in user, I would like to change password.
- As a signed in user, I would like to sign out.
- As a signed in user, I would like to create an inventory item.
- As a signed in user, I would like to update my inventory items.
- As a signed in user, I would like to delete my inventory items.
- As a signed in user, I would like to see all items.
- As a signed in user, I would like to see the quantity and price of each item.
- As a signed in user, I want to be able to update or create inventory without
having to know what my current inventory levels are.
  - If the product exists in the inventory, the app should make a PATCH request
  to update the existing item. If I don't have enough product (when reducing
  product counts) the app should not allow the update.
  - If the product does not exists in the inventory, the app should make a POST
  request to create the new item.

### Technologies Used

- React.js
- Javascript
- HTML/CSS
- Ajax
- Sass


### Unsolved Problems



## Images

#### Wireframe:
[Fridge Wireframes](.png)