# AREN_MyGreenHouse
 Google Solution Challenge Project

## Getting Started

AREN is a mobile application that presents the data from the autonomous greenhouse to the farmer with a modern result. With this application, farmers can also control the greenhouse.

## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/enesyuksel7/AREN_MyGreenHouse.git

```

**Step 2:**

Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

**Step 3:**

This project uses `inject` library that works with code generation, execute the following command to generate files:

```
flutter packages pub run build_runner build --delete-conflicting-outputs
```

or watch command in order to keep the source code synced automatically:

```
flutter packages pub run build_runner watch
```

**Note:**

The data set to be used in the phytosanitary analysis system of NVIDIA Jetson Nano in the project is located in the "dataset" folder.

```
