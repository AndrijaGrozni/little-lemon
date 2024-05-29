# 🍋 Little Lemon App

- The application is a React Native Expo Food app.
- Users will be capable of signing up on the Little Lemon restaurant app.
- Users will have to go through a registration process.
- Once they successfully complete that phase, they are redirected to a home screen.
- Home screen will represent the landing screen after completing the onboarding flow, displaying a header, a banner with a search bar and a list of menu items where a user can filter each categories.
- User can also customize their name, email, photo and and other user preferences through a Profile Screen.
- Profile screen also contains four checkboxes enable specific email notifications, like order status, password changes,special offers, and newsletters.
- Use AsyncStorage module to preserve the chosen preferences even when the user quits the application
- When clicking the Logout button, user will redirect back to login page, clearing all data saved from Profile.
- Use SQLite Database to populate, query and filter menu items.

### How to use the project

```bash
npm install && npm start
```

##### Then, a QR Code wil appear on your terminal.

##### On IOS Scan QR code through Camera app.

##### Or Locally using:

```bash
npm run ios
```

##### On Android : Scan QR code through Expo Go app.

##### Or Locally using:

```bash
npm run android
```

### Screenshot

![final_mockup](https://user-images.githubusercontent.com/108392678/217717918-a6f83c94-c1ab-4796-903e-388b9a67cdd9.jpg)
![Onboarding](https://user-images.githubusercontent.com/108392678/217715066-19026169-ab51-450e-b21c-cc925940d03e.jpg)
![Profile and Home](https://user-images.githubusercontent.com/108392678/217715079-d66eb960-f5cf-4cdf-8f33-b45b320fca7e.jpg)

### Useful resources

- [React Native Docs (StyleSheet) ](https://reactnative.dev/docs/stylesheet) - This helped me for all the neccessary React Native styles. I really liked their documentation and will use it going forward.
- [ImagePicker API](https://docs.expo.dev/versions/latest/sdk/imagepicker/) - This helped me for creating an option for user to select profile picture on their devices.
- [SQLite](https://docs.expo.dev/versions/latest/sdk/sqlite/) - This helped me for saving menu items.
- [Async Storage](https://react-native-async-storage.github.io/async-storage/docs/api/) - This helped me for saving user settings.
- [ContextAPI](https://beta.reactjs.org/reference/react/createContext)- This helped me for creating a authentication context for login.
