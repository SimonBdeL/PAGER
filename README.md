# **PAGER**

PAGER is a social app for ravers to connect and share experiences. The app allows users to join groups, discover upcoming events, make new friends, and chat with fellow ravers. With PAGER, you can easily find like-minded people to attend events with, join groups based on your music preferences, and even plan your own events. Why rave alone when you can connect with the rave community through PAGER?


## Built With

Frontend 

- React Native
- Redux
- JavaScript

Backend 

- Firebase
    - Authentication
    - Firestore
    - Cloud Messaging
    - Cloud Storage

## Technologies

![https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![https://img.shields.io/badge/Express.js-404D59?style=for-the-badge](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge) ![https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## Contributors (alphabetical order by last name)

- Simon Buret de Longagne [@SimonBdeL]([https://github.com/SimonBdeL](https://github.com/SimonBdeL))
- Andrew Heim [@andepants]([https://github.com/andepants](https://github.com/andepants))
- Madeline King [@maddieking02]([https://github.com/maddieking02](https://github.com/maddieking02))
- Abigail Li [@palmigloo]([https://github.com/palmigloo](https://github.com/palmigloo))
- Charlie Um [@charlieum]([https://github.com/charlieum](https://github.com/charlieum))
- Joshua Vilela [@joshuavilela]([https://github.com/joshuavilela1](https://github.com/joshuavilela1))
- Jeffrey Zhang [@Jeffreyzhangsd]([https://github.com/Jeffreyzhangsd](https://github.com/Jeffreyzhangsd))

## Key Features

- Firebase Services
    - Our team decided to use Firebase as it offered a wide variety of services for our product that can be easily integrated in our application such as real-time databases using Firestore, login and register account pages using Firebase Authentication , Real-time chat messages using Cloud Messaging and the ability to upload photos using Cloud Storage.
    - This allowed us to focus on the user experience without worrying about the backend services needed to run the application.

Login

- Utilized Firebase Authentication for user sign in and sign up pages
- Managed authentication screen stack flow for global state for authenticated users
- Sign up creates user and corresponding data points in Firebase Firestore with information and profile image.
    
    ![ezgif.com-gif-maker.gif](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/192b630f-c963-42c4-a5bf-274fe593c36d/ezgif.com-gif-maker.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230122%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230122T015656Z&X-Amz-Expires=86400&X-Amz-Signature=30eb385de147b78a793c9af92170d6c1e7e73a5f2f3c771d9e3278c946e0bec0&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22ezgif.com-gif-maker.gif%22&x-id=GetObject)
    

User Profile

<img width="305" alt="Screen Shot 2023-01-21 at 4 04 44 PM" src="https://user-images.githubusercontent.com/99362878/214109397-dc73cbcc-05a5-4ba4-ac03-1dc8d80caf2f.png">
<img width="305" alt="Screen Shot 2023-01-21 at 4 05 26 PM" src="https://user-images.githubusercontent.com/99362878/214109447-dbbd775c-0da5-41ba-919f-a8f7afe08153.png">
<img width="306" alt="Screen Shot 2023-01-21 at 4 05 45 PM" src="https://user-images.githubusercontent.com/99362878/214109493-66ad775e-051f-47f5-a8e0-9bb690ecfe2a.png">

- Main page showing the details of the signed-in user
- Expanded view of friends with buttons to unfriend
- Expanded view of user’s music tastes
- Edit page to edit music tastes and description

Homepage

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c4c63c0f-081a-4d3e-ab1f-19fbffbdf70d/Screen_Shot_2023-01-21_at_4.26.46_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230122%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230122T015842Z&X-Amz-Expires=86400&X-Amz-Signature=2ce82dc8774f517fbeb4efff78e807ba3162382f4b5f395487a777da868392db&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Screen%2520Shot%25202023-01-21%2520at%25204.26.46%2520PM.png%22&x-id=GetObject" width="157" height="340" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/3084586/214103264-6895f564-0c7c-4467-8360-2d09d77bc950.png" width="157" height="340" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://user-images.githubusercontent.com/3084586/214104970-d2d0f62a-8f3c-4490-b05f-18951094615d.png" width="157" height="340" />



![https://i.imgur.com/2ZDYUox.gif](https://i.imgur.com/2ZDYUox.gif)

- Swipe cards displaying groups attending events. Swipe right to join or left to pass.
- Card expanded view, showing additional information about the group.
- Filter cards based on size and vibe.

Groups

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7da4fb51-2820-4ddc-97ed-a23fd914e82e/Screen_Shot_2023-01-21_at_4.47.48_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230122%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230122T015909Z&X-Amz-Expires=86400&X-Amz-Signature=4f03fb3d37b62f05e145ba9ac7344f784dcabc2fca738d4b874915893cc4f377&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Screen%2520Shot%25202023-01-21%2520at%25204.47.48%2520PM.png%22&x-id=GetObject" width="157" height="340" />  <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/be3edd12-db3b-460a-be44-b8d6b30a13f9/Screen_Shot_2023-01-21_at_4.48.40_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230122%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230122T015911Z&X-Amz-Expires=86400&X-Amz-Signature=2d5005d416cd00528d6c3a6b6dbb668c0a4121717374d74da30b1c66761004ee&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Screen%2520Shot%25202023-01-21%2520at%25204.48.40%2520PM.png%22&x-id=GetObject" width="157" height="340" />  <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9766f863-6acd-4293-a8e1-0c8358307b2f/Screen_Shot_2023-01-21_at_4.49.16_PM.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230122%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230122T015913Z&X-Amz-Expires=86400&X-Amz-Signature=d0ddb4cb616dcfd70eaffa9ec06b16dcc39dd4822d49eee332c9d3be5ef22aec&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Screen%2520Shot%25202023-01-21%2520at%25204.49.16%2520PM.png%22&x-id=GetObject" width="157" height="340" />

All Groups

- Tabular design to view a user’s upcoming and attended groups
- Tab for user to create their own group and upload group images

Individual Groups

- Overview of group details with members and brief schedule
- Full schedule list where owner has the ability to add/delete plans

Chat

- Each individual group has their own chatrooms that they can talk with their respective members to discuss plans for their event.

Getting Started 

1. Create a Firebase project at [Firebase](https://firebase.google.com/) and create a firestore, authentication with email and password, cloud storage, and cloud messaging.
2. Input the Firebase SDK to the app’s dependencies. More details for how to do this step in the official [Firebase Documentation](https://firebase.google.com/docs/web/setup)
3. Go into the client of our repo
4. Run ```npm i``` in the terminal  

1. Run npm run start into the terminal
2. Go to [localhost:19006](http://localhost:19006) to access the app by hitting the "w" key in the terminal
