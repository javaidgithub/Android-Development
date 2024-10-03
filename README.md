From this assignment, you learned the following key concepts and skills:

1. Flutter Project Structure:
Separation of Concerns: You structured the project into separate folders (like models, widgets, and screens) which ensures scalability and maintainability.
Reusability: By breaking down the app into reusable components, such as ProductTile, you ensure that your code is modular and easy to modify or extend in the future.
2. Widget Composition:
List View and Navigation: You worked with ListView.builder to create a dynamic list of products and used Navigator.push to navigate between screens.
Full vs. Shallow Widget Trees: You applied both shallow trees (breaking down widgets into components) and full widget trees (where everything is composed within a single build method), understanding how to manage complexity.
3. Handling Images in Flutter:
Image.network: You learned how to load images from the internet.
Error Handling in Images: By implementing errorBuilder, you ensured that your app gracefully handles cases where the image URL is incorrect or the image fails to load.
4. State Management:
While this assignment focused on stateless widgets, you were introduced to basic state management in the form of passing data between screens (e.g., Product details).
5. Working with Layouts:
Flexibility with SizedBox and BoxFit: You learned how to control the size and behavior of images and other UI components, making the app responsive and visually consistent.
CrossAxisAlignment and MainAxisAlignment: These helped you align content properly within your widgets.
6. Handling Errors and Debugging:
Error Handling with Widgets: You explored how to deal with failed network requests (e.g., loading images from the internet) and how to debug issues like broken URLs.
7. Custom Styling:
Background Colors for List Items: You added custom styling to enhance the UI by alternating background colors for better readability.
Dynamic UI Elements: By changing how the products are displayed, you demonstrated the ability to customize the user interface based on data and interaction.
8. Navigating Between Screens:
You implemented navigation between the product list and the product details screen, showcasing how to pass data (i.e., Product objects) between different views.
