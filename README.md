# ⛳ Hole Track ⛳

Hole Track is a mobile app where the user is able to track scores while playing any type of golf version. It could be mini-golf, soccer-golf, even standard golf. All the user needs to do is enter the player names, amount of holes and easily keep track of rounds and scores.

<img width="200" height="450" alt="Screenshot 2026-05-21 133914" src="https://github.com/user-attachments/assets/e21304f7-fcc3-4cc8-a228-96eb1da16784" />

<img width="200" height="450" alt="Screenshot 2026-05-21 134015" src="https://github.com/user-attachments/assets/80d7661b-afcd-4640-a630-76186e7af3f5" />

<img width="200" height="450" alt="Screenshot 2026-05-21 134056" src="https://github.com/user-attachments/assets/d62d2fe0-12be-4566-ad0c-40bd791f1c02" />

<img width="200" height="450" alt="Screenshot 2026-05-21 134153" src="https://github.com/user-attachments/assets/1026a832-c5f8-4169-a3af-05e56580f48f" />


---

## ✅ Test the app ✅

- Web Build: [Test Here](https://laratastudios.com/HoleTrack-Public/)
- Android Apk: [Download](https://github.com/LARAta-Studios/HoleTrack-Public/releases/tag/Apk)

---

## 💫 Features 💫
- Dynamic player creation before starting game
- Custom match/session setup with configurable number of matches
- Responsive layouts for mobile and web
- Back navigation protection with warning dialogs
- Custom leaderboard screen
- Custom App Icons for Android, IOS, Web
- Clean modern UI using green color palette and Space MOno typography
- Apk and web export for easy share and testing


---

## 🛠️ Built With 🛠️

- Flutter
- Dart
- GitHub Pages

---

## 💡 Important Design Decisions 💡

Throught this project I had to take multiple important decisions regarding the projects future. Some of them were:

### 🚩Lowest-score-wins scoring system🚩
Although the word scoring often refers to the maximum amount of points reached I knew that this app had to be different because of how performance is checked in golf. In golf the least score wins, so essentially the fastest player is the winner.
Starting the project with this in mind proved to be helpful for the last portions of the project.


### 🏁Early-finish architecture🏁
Since this is an app that I came up with because of my necessity of one when I am out playing mini-golf with my family, I often designed features based on the needs that me (a user) would need and one of them was this one, being able to end the game suddendly because of
something that happened and being able to declare the winner. This turned out to be even more helpful in the end because if the user doesnt know how many holes the golf course has they can chose 18 and if they reach the end and the last one was 14, then the user wouldn't
have to manually pass the last 4 rounds, they can just finish "early" and get the results. 



### 🎨Responsive UI🎨
This is something that I failed to think about at the beginning of the project, which did cost me a little bit of wasted time. Since phones have different display layouts like on-screen back and home buttons, others have swipe actions instead I found the UI did not 
adapt very well, so I had to restructure the UI by using SafeArea() widgets and it ended up solving later issues for the same reason like different browsers (Safari and Chrome).

---

## 🎓 What I learned 🎓

This project taught me:
- Basics of Dart
- Basics of Flutter
- State management and passing complex objects between pages in flutter
- Build responsive layouts for mobile and web
- Structuring applications using reusable data models
- Building and deploying Flutter web applications
- Foundamentals of mobile development
- Using setState() effectively for live UI updates

---

## 🎯 Technical Challenges 🎯

- Resposive Layout issues: as mentioned before the recurring challenge of things not fitting in a specific screen came up fairly recent, specially when working on a new page of the app, This required me to restructure the layouts by using SingleChildScrollView widget, using responsive spacing
and user SafeArea() widget to wrap the main widget of each page.
- Hero tag conflicts: Due to it being my first time using flutter I ran into the issue of using multiple hero widgets dynamically which cause dduplication of hero tags during navigation transitions. This was solved by assigning unique tags to each hero widget to avoid duplication errors.


---

## 🔮 Future Improvements 🔮

- Persistent save/load system for unfinished games
- Local database save support
- Animated leaderboard
- Dark mode support
- Multi-language support
- Deploy in Appstore and Playstore


---

## ⚙️ Source Code ⚙️

The full source code is private while the project is in active development.
This repository serves as a showcase of the project, including gameplay footage, technical explanations and playable builds. 
