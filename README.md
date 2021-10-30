# maps_example

## Getting Started

This project is a starting point for getting Google Maps integrated into your Flutter app using the [google_maps_flutter](https://pub.dev/packages/google_maps_flutter) package.

This project was made by combining the [pub.dev package set up instructions](https://pub.dev/packages/google_maps_flutter) and removing API keys from source in [this Medium article](https://medium.com/@ykaito21/flutter-from-zero-to-one-how-to-ignore-google-map-api-key-from-source-control-18e119ff5a47). 

# Installation

Ensure you have flutter installed correctly by running `flutter doctor`. You should get all green ticks. 

Create and Add Maps API keys for iOS and Android from [GCP](https://console.cloud.google.com/google/maps-apis/credentials) to `ios/Runner/APIKey.plist` and `android/app/src/main/res/values/keys.xml` respectively. 

Then `flutter run`, or in VS Code select your simulator device and run. 

You will get a basic full screen google map with a button allowing you to pan/zoom/focus to a particular Latitude/Longitude location. 

