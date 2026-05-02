# Baby CountDown Page 

## How to deploy in firebase
- first ensure gcloud is installed an logged in 
- create a firebase project https://console.firebase.google.com/ 
- ensure firebase is login `npx firebase-tools login`
- init workspace `npx firebase-tools init hosting`
- subsequence deployment `npx firebase-tools deploy --only hosting`
