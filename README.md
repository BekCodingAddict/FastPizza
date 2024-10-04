# FastPizza

> [!NOTE]
> The Fast React Pizza app is a modern, multi-page pizza ordering web application built using React and a variety of supporting technologies. The main purpose of this project is to provide a fully functional pizza ordering system where users can browse pizza options, add items to a cart, view detailed orders, and manage their profiles.

### Project Requirments:

- [ ] Very simple application, where user can order one or more pizzas from a menu
- [ ] Required no user accaunt and no login:users just input their names befor useing app
- [x] The pizza menu can change, so it should be loaded from an API
- [ ] User can add multiple pizzas to a cart befor ordering
- [x] Ordering requires just the user's name,phone number, and addres
- [ ] If possible, GPS location should also be provided, to make deliver easier
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
