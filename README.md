# Safe Keeping

### Summary

Safe Keeping is a diary tracker and emotional first aid kit designed to help people learn and practice coping skills and track their daily mental health. 
Users can add therapists who can view their progress through the companion web app.

### Tech Stack
* Rails API backend. PostgreSQL database.
  * Gems: bcrypt, JWT, Active Model Serializers, CORS.
* React Native w/ Redux mobile app.
  * Libraries: React Native Calendar, React Native Slider, Expo SecureStore, React Native Modal Datetime Picker, React Native Reanimated, React Native Gesture Handler, React Native SVG.
* React w/ Redux web app.
  * Libraries: Victory.

### Installation
###### First clone the frontend(s) and backend.
- [Link to mobile frontend](https://github.com/blobbyblobfish/safe-keeping-frontend-mobile)
- [Link to web frontend](https://github.com/blobbyblobfish/safe-keeping-frontend-web)
- You are reading this on the backend README.

###### Commands
1. Run `bundle install` in the backend directory. Run `rails db:migrate`.
2. Run `rails s` and open the server on port 3000.
3. Run `yarn install` in both frontend repositories.
4. Start expo in the mobile directory using `expo start` and run the app in a device simulator. You may have to use the most recent LTS node version.
5. Start the web app on an open port using `yarn start`.
