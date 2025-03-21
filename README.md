# Module06CourseProject
Link: 

## Purpose of the Site
The application revolves around the information of fruits in a fun and easy way. Users can look at a grid of fruit pictures, open a panel with nutrition info, fill out a personal form, and save their favorite fruits using the browser’s localStorage. The form collects name, email, age, sex, comment, and an optional favorite item which is stored locally to allow the user to interact with the app repeatedly. The collected data is saved and later displayed in the “Favorites” section available on a separate page which is fetched from the local storage. A custom theme template with a design that is clean and simple for mobile user is provided which ensures the UI is consistent throughout the application. 

## Website Structure (Site Map)
![Drawing 6(2)](https://github.com/user-attachments/assets/61db1313-a812-4301-b041-c66b2dec18cf)

## Buttons & User Interactions
On the Main Page, users interact with several navigation options. Clicking the “Fruit Info Panel” button opens the pulls the side panel from the left containing elaborated information regarding the benefits fruits provide for health. Users have the option to close this panel by clicking outside of it, hitting “Esc" button, or swiping.
On the main page also are three links to navigate pages: “Grid List of Fruit”, “User Form”, and “Favorites List of Fruits”. Selecting the “Grid List of Fruit” option takes users to a pictorial array of fruits displayed in a responsive three-column grid which serves as a gallery with each fruit containing an image and a caption.
The “User Form” link takes one to a form page where a user can give in his or her name, email, age, gender, comments and even their favorite fruit The moment the “Save” button is pressed his data is stored using localStorage and a bounced alert thereby showing what he submitted as the data. And when “Clear Data” button gets clicked the form will reset and all data in localStroage is erased.
In the end users can access the page by clicking “Favorite List of Fruits” which will automatically load a list of their highlighted fruits. These highlights are fetched from local storage and are displayed as a simplistic list every time the page is opened.
