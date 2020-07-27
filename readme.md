# Demo Integrate React Native

## Description

Integrating react native with existing Android and iOS native projects.

## How to run

- Clone this repository.
- At root directory run `yarn install` to install the dependencies.

##### Android

- Open folder `android` by Android Studio and run the project as normal.

##### iOS

- At root directory `cd ios/ && pod install`
- Go to `ios` folder and double click `DemoIntegrateRN.xcworkspace` to run the project.

##### Run the packager

- To run react native part, you need to first start the development server. To do this, run the following command in the root directory `react-native start`
- From the native app and clicking the button to navigate to react native part, it should load the JavaScript code from the development server and display react native screens.
- To run in release mode, no need to start the development server. Just run the `yarn run build:ios` command to generate the bundle and start the app
