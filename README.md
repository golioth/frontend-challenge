## Frontend Code Challenge

### Project

A company wants to develop a home grown fresh plants monitoring system for casual users. The hardware development is still happening, but they want to be in touch with their future customers by providing a solution that already works without their IoT hardware for now and starting collecting feedback from them.

These are the high level requirements for the system:

- User Registration
- Add/Remove plants/herbs
  - Give it a name and/or type - ex: Thyme, Basil, Lettuce, etc
- Register health/status for a given plant and save that as a historical information ( will be captured by the IoT device later )
  - Soil moisture - 0-100%
- User Dashboard
  - Show health status of each plant for the user
  - Can also show current weather on users location (optional)

Feel free to add or change things on top of that idea. For example, you can register other attributes of the plant, show charts, simulate real time data changes, etc. For the current weather, you can get user location from the browser and use a third party API for weather info.

### Technical Requirements

- React (preferably Typescript, but optional)
- State Management (MobX, Redux, Hooks, etc)
- CSS (styled-components, CSS modules, or plain CSS/SASS/LESS)
- Backend
  - For this you can simulate using something like a backend as a service solutions, like Firebase, AWS Amplify, Hasura, DGraph or just local with tools like Miragejs and Json-server.
- Authentication
  - For this you can offload that to an identity provider like Auth0, Firebase Auth, Cognito, Okta, etc.

### Deliverables

- Link of your public Github repo
- Link of your Prototype/Wireframe (Figma, Whimsical, etc) (optional)
- A live working demo of the application (Github pages, Netlify, etc) (optional)
- A video of the application working (There's no need to voice over it, neither webcam or anything fancy. Loom is nice tool for that) (optional)

### Hints

- You don't need to spend time creating a dev/build environment. You can use create-react-app (and other alike tools) for that
- Third-party libraries are allowed.
- As a company, we believe that communication is the key to success. So if something is not clear to you, or if you have doubts on what you can use, reach the devs

### Happy coding!

<img src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" data-canonical-src="https://user-images.githubusercontent.com/5693916/30273942-84252588-96fb-11e7-9420-5516b92cb1f7.gif" width="150" height="150" />

#### References

- https://whimsical.com/
- https://miragejs.com/
- https://github.com/typicode/json-server
- https://firebase.google.com/
- http://auth0.com/
- https://hasura.io
- https://medium.com/@Ari_n/8-weather-api-alternatives-now-that-darksky-is-shutting-down-42a5ac395f93
