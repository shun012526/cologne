<template>
  <div>
    <Nuxt />
  </div>
</template>
<!-- The core Firebase JS SDK is always required and must be listed first -->
<!--
<script src="https://www.gstatic.com/firebasejs/7.20.0/firebase-app.js"></script>
-->
<!-- TODO: Add SDKs for Firebase products that you want to use
https://firebase.google.com/docs/web/setup#available-libraries -->
<!--
<script src="https://www.gstatic.com/firebasejs/7.20.0/firebase-analytics.js"></script>
-->

<!--
<script>
  // Your web app's Firebase configuration
  var firebaseConfig = {
    apiKey: "AIzaSyDZoweGtSpypceKu3hku8ThZMYvk9flIEw",
    authDomain: "cologne-web.firebaseapp.com",
    databaseURL: "https://cologne-web.firebaseio.com",
    projectId: "cologne-web",
    storageBucket: "cologne-web.appspot.com",
    messagingSenderId: "341064514781",
    appId: "1:341064514781:web:b4014dab4cbafc254daf34",
    measurementId: "G-52C7EJ4P05"
  };
  // Initialize Firebase
  firebase.initializeApp(firebaseConfig);
  firebase.analytics();
</script>
-->

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
