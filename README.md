# CS-360 Portfolio

## Mobile Architecture and Programming

This repository contains my completed Project Three Inventory App from CS-360 Mobile Architecture and Programming. The project demonstrates the skills I developed throughout the course in mobile application design, Android development, database management, testing, and user-centered design.

The completed app code design is included in the `Fish_Jeremy_ProjectThree.zip` file.

## Project Reflection

### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of my project was to develop a functional Android inventory application that allows users to create an account, log in, and manage inventory information from a mobile device. The application needed to store user account information and inventory data using a SQLite database so that the information could be managed through the app. For the inventory itself, users needed the ability to enter an item name and quantity, add that information to their inventory, view their items, and remove items when they were no longer needed.

The main user need I wanted to address was making inventory management simple and convenient. Instead of creating an application with unnecessary screens or complicated navigation, I focused on the basic actions someone would regularly need when keeping track of inventory. A user should be able to open the app, access their account, see what they have in inventory, and make changes without having to figure out a complicated interface.

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

Several screens and features were important to supporting the needs of the user. The application needed account and login functionality so that users could access the app through their own credentials. The main inventory interface needed to clearly display inventory information while also giving users controls for entering an item name and quantity, adding an item, and deleting an existing item. Displaying the inventory information in an organized grid or table made it easier for the user to quickly understand which items were being stored and how many of each item were available.

When designing the UI, I tried to think about what I would expect if I were using the application myself. I kept the controls straightforward and used recognizable buttons and text fields instead of making the user navigate through unnecessary menus. I also tried to keep related information close together. For example, the item name and quantity fields are located near the control used to add an item. I believe the design was successful because the interface supports the main purpose of the application without overwhelming the user. This project showed me that a good mobile interface does not necessarily need to be complicated. It needs to make the user's most important tasks easy to understand and complete.

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the coding process by breaking the application into smaller pieces instead of trying to develop everything at once. I first worked from the UI that I created during Project Two and then added the functionality required for Project Three. One important part of the process was separating the database responsibilities from the main activity logic. I used a `DatabaseHelper` class with SQLite to handle the application's database operations. The database included tables for user information and inventory information, while the activity code handled interactions between the interface and the user.

I also relied on incremental development. I would add or modify one part of the application, run it, and then determine what needed to be corrected before moving forward. This helped make troubleshooting more manageable because I had a better idea of which change might have caused a problem. I can use the same strategy in future projects by dividing larger applications into smaller components, testing features as they are developed, and keeping data management separate from UI logic whenever possible. This makes the code easier to understand, maintain, and improve.

### How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application primarily through Android Studio and the Android Emulator. Rather than only checking whether the project compiled, I tried to interact with the application the way an actual user would. This included entering information into the inventory fields, adding inventory items, checking that the information appeared correctly, and testing the delete functionality. I also paid attention to input validation so that the application could respond appropriately when required information was missing or invalid.

Testing was especially important because an application can compile successfully and still have problems with its actual behavior. Running the app helped reveal issues that would not always be obvious just by reading the code, including problems with navigation, UI behavior, database interaction, and emulator performance. The testing process taught me that development and testing should happen together throughout a project rather than treating testing as something that only happens after all of the coding is finished.

### Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of my biggest challenges during this project was working through technical and performance issues while continuing to make progress on the application. Android Studio and the emulator could sometimes run slowly or freeze, which made testing more difficult than I originally expected. I had to adjust how I worked by testing smaller changes, being patient with the emulator, and focusing on one feature at a time instead of making many changes before running the application again.

Another challenge was moving from the visual design created in Project Two to an application that actually performed the required functions in Project Three. A screen can look correct without having the code behind it to make the buttons, database, and user input work together. I had to think beyond the appearance of the app and connect the UI elements to Java code and SQLite database operations. Working through that process helped me become more comfortable troubleshooting and adapting when the first approach did not work as expected.

### In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful with the inventory management and database portion of the application. I created a SQLite database structure that could support both user accounts and inventory data. The inventory functionality connected user input from the interface with the application's underlying data and allowed information such as item names and quantities to be managed through the app.

I am also proud of how the final project brought together concepts from multiple stages of the course. The UI began as a design project, but by Project Three it had become part of a functioning Android application with Java logic and persistent data management. Seeing those separate pieces come together helped me better understand the full mobile development process. This project demonstrates not only my ability to design a mobile interface, but also my growing ability to connect the interface, application logic, and database into one complete application.
