# Flow - Just go with the flow!
Flow is a water source location mobile app that helps students of the University of Bamenda, Cameroon to find/locate clean water sources.

<img src="https://github.com/Idadelveloper/Flow/blob/main/Assets/flow_mockups/flow2.jpg" />


## Introduction
Flow came about as a result of the persistent water crises in Bambili, Cameroon. This is the location of the University of Bamenda in the North West Region of Cameroon. Due to the high influx of people(students) into this locality, water shortages have been the order of the day. The water is being rationed to ensure everybody gets water (unfortunately not everyone gets water as there are times some areas go weeks without water).

Let's consider two locations in Bambili A and B. As a result of the overpopulation leading to water shortage, there could be water today at A and maybe tomorrow at B. The next day there might be no water at at A and B forcing students to go to say another location, C in search of water. Chances are there might be no water at C and now the students will be forced to go to D. Bottom line nobody knows where exactly water is flowing neither does evrybody know all the possible locations of getting water in Bambili. There are locations which go weeks or months without water; it's very difficult especially for new people in the community to find water. This is where flow comes in to save the day!


## Key Features
* Locate all clean water sources around you by radius.
* Show approximate distance from user to a water source.
* Get directions to the water source.
* Save your favourite water sources.
* Indicate if water is flowing at a water source or not.


## Get the App!
You can get the .apk file [here](https://drive.google.com/file/d/1va0lWRXwSoB2xYVLwT24dVqEFrWPnXFJ/view?usp=sharing).
Download and install the app.
## Usage
* Open the app.
* Explore!
* You can also learn how the app works [here](https://flow-online.ga/)

## How to Build
Follow [this](https://flutter.dev/docs/get-started/install) tutorial on how to install and set up flutter for mobile development.
Clone the repository:
``` git clone https://github.com/Developer-Student-Clubs-UBa/Flow.git ```

### Requirements
The following Flutter dependencies are required:
*  flutter_svg: ^0.19.1
*  google_maps_flutter: ^2.0.1
*  location: ^4.1.1
*  cloud_firestore: ^1.0.3
*  firebase_core: ^1.0.2
*  shared_preferences: ^2.0.5
*  flutter_polyline_points: ^0.2.6

Include the package name and version number in the pubspec.yaml file below the dependencies section.

#### Steps to run
* Open the project on Android Studio.
* Get your Google Maps API key. For Android, follow instructions [here](https://developers.google.com/maps/documentation/android-sdk/get-api-key)
* Add the API key to your Flutter app in the application manifest (android/app/src/main/AndroidManifest.xml), as follows:
```
<manifest ...
  <application ...
    <meta-data android:name="com.google.android.geo.API_KEY"
               android:value="YOUR ANDROID API KEY HERE"/>
```
* Run the code on Android studio and view the app on your emulator of choice or mobile device. You can also run the app from the terminal using:
``` flutter run ```

Build the application following this [tutorial](https://flutter.dev/docs/deployment/android).

#### TODOs
* ~~Make the get directions feature fully functional.~~
* ~~Distance Calculation.~~
* Implement a voting system to indicate if a water source has water supply or not.


#### Contributors
* Ida Delphine
* Nuikweh Lewis 
* Alouzeh Brandone
* Chi Karl
