React Native Shopping Cart App (rn-assignment7-11100877)
This React Native application implements a shopping cart functionality with product browsing, detailed product views, cart management, and local storage.








Features:

Fetches product data from an external API.
Displays a list of available products on the HomeScreen.
Allows navigation to a detailed ProductDetailScreen for each product.
Provides an "Add to Cart" button on product details.
Displays a CartScreen showing selected items.
Enables removing items from the cart.
Utilizes Local Storage (AsyncStorage, SecureStore, or FileSystem) to persist cart data.







Implementation Details:






Components:
HomeScreen: Renders product list using fetched API data (potentially FlatList/SectionList).
ProductDetailScreen: Displays detailed product information and "Add to Cart" functionality.
CartScreen: Retrieves and displays cart items stored in Local Storage.
Drawer/Navigation Menu: Provides navigation options between screens (optional, using libraries like React Navigation Drawer).








Functionalities:
Fetches product data using fetch or axios with asynchronous operations (async/await or promises).
Stores and retrieves cart data using Local Storage libraries.







Additional Considerations:
Error handling for API calls.
User Interface based on the provided UI mockup (if available).
Unit testing for components and functionalities (recommended).








Screenshots:









![WhatsApp Image 2024-07-12 at 13 59 38_d818f051](https://github.com/user-attachments/assets/0c8ed91d-dcc5-4fe5-9e30-869e365675fd)









![WhatsApp Image 2024-07-12 at 13 59 39_be8b4df0](https://github.com/user-attachments/assets/fc01750d-5a28-42fa-a992-9e9ba7cc9bfe)


