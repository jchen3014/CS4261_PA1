# iOS Weather App
 Programming Assignment for CS4261.
 
 It's a simple weather app that uses OpenWeatherMap API to provide users with weather data. "Add Entry" button stores data into Firebase Database. "Authorize" button authenticates user using FaceID to enter a private page.

 <br>
 <br>
 
 <p align="center">
 <picture>
 <img alt="weather-app-UI" height="500px" src="https://drive.google.com/uc?id=1xcjzTCfMJMpzKflhHwewDxBKDk6ERazJ">
 </picture>


# Info

In order to run the application, you need to install the required Firebase repositories when this project in XCode (if XCode does not handle it for you) to use the app's features. XCode should handle all of the Firebase dependencies, so the user should not need to create their own database and can use the GoogleService-Info.plist provided in the repo. 

Get your Weather API key here: https://openweathermap.org/

# Installation/Build Instructions
1. Make sure you have Xcode on your system
2. Download project from Github link
3. Click the Weather API link and sign up to get your personal API key
4. Open the project folder
5. Double click the file named “projet_meteo_ios_marelk.xcworkspace” to open it in Xcode
6. Open the project is opened, click on the folder icon at the top left of the window
7. Click on projet_meteo_ios_marelk on the left-hand side
8. Under TARGETS, select “projet_meteo_ios_marelk”
9. Go to Signing & Capabilites -> Team -> select yourself (see the image under ChatGPT)
10. Go to WeatherManager.swift and replace “2148d15372c6bca829f403c4d7a8c9af” with your personal API key in the baseUrl.
11. Build and run the application
12. Note on how to use FaceID in simulator: once the app is running, click on Features -> FaceID -> Enrolled. Then, click the Authorize button on the screen. Once the FaceID window pops up, click Features -> FaceID -> Matching Face.
13. Clicking the Add Entry button adds an entry to the real-time database
