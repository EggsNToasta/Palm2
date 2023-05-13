<script lang="ts"> 
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";

const firebaseConfig = {
  apiKey: "AIzaSyDIMjOifygWpys5pGsRx4zGsNfRQoFxuv8",
  authDomain: "terraform-project-11.firebaseapp.com",
  projectId: "terraform-project-11",
  storageBucket: "terraform-project-11.appspot.com",
  messagingSenderId: "17722932885",
  appId: "1:17722932885:web:c96c9d1b803a77c1b9e59c",
  measurementId: "G-BD6ZK5NKYK"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

</script>