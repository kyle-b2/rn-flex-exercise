# Creating a Single-Page React Native Application
Manage user profiles with some specific features for a mobile app. Here's what you need to do:

1. **Fetch User**: Implement a fetch function to fetch a user on button click from the provided API and display the profile with the card component.
2. **Header**: Display a header that reads "Welcome to the app, \$USER!".
3. **State Synchronization**: Sync the value of the user's name to the header.
4. **User Card**: Create a card component that displays a user's profile picture, name, email, and phone number.
5. **Editable Fields**: Allow users to edit the name, email, and phone number via an Edit -> Save button at the bottom of the card. Implement a function to save the edited version to the API, and refresh the data immediately.
6. **Swipe to Get New Profile**: EXTRA CREDIT - Implement a swipe gesture to fetch a new user profile.

API endpoints:\
URL: `https://interview-api.flexbase.workers.dev`\
Returns a list of user profiles: `GET /users`\
Edit user info (email and name): `PATCH /users/:id`\

# Snack app details

Open the `App.js` file to start writing some code. You can preview the changes directly on your phone or tablet by scanning the **QR code** or use the iOS or Android emulators. When you're done, click **Save** and share the link!

When you're ready to see everything that Expo provides (or if you want to use your own editor) you can **Download** your project and use it with [expo cli](https://docs.expo.dev/get-started/installation/#expo-cli)).
