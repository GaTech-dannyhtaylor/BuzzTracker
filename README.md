# BuzzTracker

BuzzTracker is an Android donation tracking application catered to non-profit organizations for efficient tracking of incoming and outgoing goods. It handles registration, authorization, inventory, and map views. A previous version did have the app connected to a FireBase DB, but for long term project storage we decided to save data to local file storage. 

## About This Project
This project was created as a semester long group project for CS2340 - Program Design Paradigms at Georgia Institute of Technologies in fall 2018. Each group consisted of 4-6 members. BuzzTracker is a product of the group's efforts. However, I, Danny Taylor, was mainly responsible for the following, though I assisted in other areas as well:

1. Overall UI Design
2. Log-In Authorization Business Logic
3. Inventory Search Funcationlity


Our team, "BinaryBros" consisted of:

#### Team Binary Bros
* [**Joe Miano**](https://github.com/jmiano)
* [**Fidel Flores Caceres**](https://github.com/fefcaceres)
* [**Danny Taylor**](https://github.com/dannyht)
* [**Walker Smith**](https://github.com/walkersmith2021)
* [**Zheheng Fan**](https://github.com/zfan71)

The project was divided into milestones that spanned the entire semester. The milestones were:

1. M1 Team and Project Management
2. M2 Version Control
3. M3 Individual Android Assignment
4. M4 Project Setup, User Stories, and Login/Logout
5. M5 Domain Model and Registration
6. M6 - Software Architecture, UI Prototypes and Read Location Information
7. M7 - UML Class Diagram and Add a Donation Item
8. M8 - Donation Item Search, Persistence and UML Sequence Diagram
9. M9 - Method Contracts and Map Display
10. M10 - Code Quality and Unit Testing
11. M11 -- Individual Case Study

## Demo

A video showing the application can be seen here:


## Installation & Testing
You will need to install Android Studio to view this project. However, it's advisable to first install java on your system first. Java 8 installed on the systems that developed this app, but any version higher should work fine.

To check to see if java is installed: `java -version`
If you need to install the java sdk, [here](https://java.com/en/download/help/download_options.html) is a guide to installing java.

[Here](https://developer.android.com/studio/install) is a guide on installing Android Studio.

After installing Android Studio, import the project. Then go to your "AVD Manager" to create a new virtual device. When creating a new device, you can select any API 28+, but make sure you at least download API 28 (even if you don't want to use it) or else you will run into errors.

Run the project and enjoy!
