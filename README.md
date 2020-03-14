# Welcome to Self-Reliance's Github Page!

## We are developing our own framework for interactive video games and is going to update it with the newest 5th episode!

## TODOs: 
0. Add change language function to Erolingo.
1. Remove all the third party dependencies : ToastMe, DoozyUI, I2 Localization,AVPro Video.
2. Make own Video Player(Or find a way to use native Video Player), include Decode/Encode for different platforms.
3. Build a friendly UI so everyone can use it.
4. EroLingo Cloud Sync.
5. Eroidea Cloud Sync.
6. Cloud Sync Build New Content.
4. Always Fix the Bugs.

Ero OS is a visual novel framework created by Eroducate. It allows you to create your own visual novel game(Video Content) without writing a single line of code. Ero OS currently includes two parts: Eroidea, Erolingo. Ero OS is currently under development and it uses third party dependencies. We hope to remove all of them and bring everyone a free tool to create your own visual novel game.

## Eroidea
Eroidea is the core part of Ero OS. It connects all the prefabs and script calls, and it is also the main logic system of the game itself. By using the control panel on Eroidea, you can simply add choices and use built in pause/skip functions inside the game.

## Erolingo
Erolingo is the language management system of Ero OS. It allows you to change languages(Under Development) and to create several translations for one term.

### Data Structure

Clip:
    Clip is the most important structure inside Ero OS since the system drives this data all the time. One clip includes a ChoiceHolder(The GameObject we use to hold choices), Video Playlist, and Importance. 
     