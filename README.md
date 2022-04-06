
## Configuration
To use this project with Firebase authentication, some configuration steps are required.
  1) Create a free Firebase account at [Firebase](https://firebase.google.com)
  2) Create a project from your [Firebase account console](https://console.firebase.google.com)
  3) Configure the authentication providers for your Firebase project from your [Firebase account console](https://console.firebase.google.com)
  4) Configuration required to connect to Firebase is defined in the `.env.local` file in the root of this repository
```js
VUE_APP_FIREBASE_API_KEY='<YOUR-API-KEY>'
VUE_APP_FIREBASE_AUTH_DOMAIN='<YOUR-AUTH-DOMAIN>'
VUE_APP_FIREBASE_PROJECT_ID='<YOUR-PFOJECT-ID>'
VUE_APP_FIREBASE_STORAGE_BUCKET='<YOUR-STORAGE_BUCKET>'
VUE_APP_FIREBASE_MESSAGING_SENDER_ID='<YOUR-MESSAGING-SENDER-ID>'
VUE_APP_FIREBASE_APP_ID='<YOUR-APP-ID>'
```
  5) In order for this application to work you will have to obtain an API key from [TMDB](https://www.themoviedb.org/settings/api). Once you get the key, you must insert it in a file `.env.local`
```js
VUE_APP_TMDB_API_KEY='<YOUR-API-KEY>'
```

## Installation
Clone project:
```shell
https://github.com/Ismail-Mouyahada/cesi-netflix.git
```

Then change into that folder:
```shell
cd cesi-netflix
```

Install project dependencies:
```shell
npm install
```
(You may have to install vue-cli-service if it's not already done)

```shell
npm install @vue/cli-service
```


Build for production:
```shell
npm run build
```

Start up a local server:
```shell
npm run serve
```

Open [http://localhost:8080](http://localhost:8080) to view it in the browser.
 
 
