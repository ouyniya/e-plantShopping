# 🌿 e-Plant Shopping Website

A beginner-friendly e-commerce web app for plant shopping built with React. This project is part of the IBM Full Stack Developer Skills Network training program.


## 💡 Demo

https://ouyniya.github.io/e-plantShopping/


## 🛠️ Key Features & Learning Highlights
### 🌱  Plant Display:
The app dynamically displays a list of plants using plantsArray in ProductList.jsx, rendering details like name, category, image, description, and cost inside a div with the class product-grid.

### 🛒 Add to Cart Functionality:
Clicking "Add to Cart" triggers the handleAddToCart() function, which dispatches the selected plant to the Redux addItem() reducer in CartSlice.jsx.

### 🔁 State Management with Redux:
The CartSlice.jsx file handles adding, removing, and updating plant quantities using reducer functions (addItem, etc.). These reducers manage the cart's state centrally.

### 🧩 CartItems Component:
This component displays cart contents, enables quantity updates, subtotal and total calculations, item deletion, and supports "Continue Shopping" flow.

### 🌐 Deployment:
The app is deployed via GitHub Pages


## 🎯 Learning Objectives
- Build reusable React components with props and composition.
- Use React Hooks like useState and useEffect for state and lifecycle handling.
- Apply Redux for global state management (actions, reducers, store).
- Dynamically render UI from arrays using map().
- Handle user events and apply conditional rendering logic.




## ✅ License

This project is based on https://github.com/ibm-developer-skills-network/e-plantShopping, which is licensed under the Apache License 2.0.  
  
Modifications have been made by Ouyniya.

See the [LICENSE](LICENSE) file for more details.