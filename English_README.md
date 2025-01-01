# 🍕 What is Fast Pizza React App?

> [!NOTE]
>The Fast Pizza React App is a modern, multi-page pizza ordering web application built with React. It provides users with a convenient platform to browse pizza options, add items to a cart, and place orders without the need for creating an account. The app is designed to be simple, intuitive, and easy to use for pizza lovers everywhere.

### Project Requirments:

- [x] Very simple application, where user can order one or more pizzas from a menu
- [x] Required no user accaunt and no login:users just input their names befor useing app
- [x] The pizza menu can change, so it should be loaded from an API
- [x] User can add multiple pizzas to a cart befor ordering
- [x] Ordering requires just the user's name,phone number, and addres
- [x] If possible, GPS location should also be provided, to make deliver easier
- [x] User's can make their order as "pirority" for an additional 20% of cart price
- [x] Orders are made by sending POST request with the order data (user data+selected pizzas) to the API
- [x] Payment are made on delivery, so no payment processing in necessary in the app\
- [x] Each order will get a unique ID that should be displayed, so the user can later look up their ordeer based on the id
- [ ] Users should be able to mark their a s"priority" order even after it has been placed

### Features and Pages

| Featured Categories | Necessary pages   | URL Params      |
| ------------------- | ----------------- | --------------- |
| User                | HomePage          | /               |
| Menu                | Pizza menu        | /menu           |
| Cart                | Cart              | /cart           |
| Order               | Placing new order | /order/new      |
| Order               | Looking up order  | /order/:orderId |

### Technologies & Tools:

<p>
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/reactrouter/reactrouter-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-original.svg" title="npm" alt="npm" width="40" height="40"/>&nbsp;
</p>

## Key Features of Fast Pizza App:
### 🛒 Pizza Menu
- The pizza menu is dynamic and can be updated easily through an API, ensuring that users always have the latest options to choose from.
### 👤 No User Account or Login
- Users don't need to create an account to place an order. All that is required is their name before they start using the app.
### 🍽️ Order Multiple Pizzas
- Users can add one or more pizzas to their cart before placing an order, making the process flexible and customizable.
### 📍 Location Services
- For ease of delivery, users can provide their GPS location, which helps ensure accurate delivery to their doorstep.
### 💳 Order Priority
- Users can mark their orders as "priority" for an additional 20% of the cart price, ensuring faster delivery.
### 📦 Unique Order ID
- Every order receives a unique ID, allowing users to track or look up their orders later.
### 📱 Order Form
- To place an order, users only need to input their name, phone number, and address. No payment processing is required within the app, as payments are made on delivery.
### 🛑 Post-Order Priority Update
- Even after placing an order, users can still update their order to "priority" status, giving them flexibility in managing their orders.

