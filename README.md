CONTENTS




ABSTRACT

Chapter	Name of the Chapter	Page No.

1.	        INTRODUCTION
	 Problem Statement                                                    1
	 Objectives                                                                 1
	 Motivation                                                                1
	
2.	        LITERATURE SURVEY
                                                                    Existing System                                                     2
                                                                    Proposal System                                                    2
                                                                                  Summary                                                               2



3.	       SOFTWARE REQUIREMENTS                                                                                           S     SPECIFICATIONS   
	External Interface Requirements                              3
                                                                   Non-Functional Requirements                                 4
           
4.	         SYSTEM DESIGN             
	System Architecture                                             5
	Use Case Diagram                                                6
	Entity Relationship Diagram                                8
	Database Entries                                                   9
	Android Application Design                                12
	Activity Diagram                                                 13
	Class Diagram                                                     14
	
5.	        IMPLEMENTATION
	Environmental Setup	15
	Module Description	18
	Software Description	24
                                                                   Sample Code	25
	
6.	       SYSTEM TESTING
	Tests	35
	
7.	      RESULTSCREEN SHOTS                     36
	
8.	      CONCLUSION	                              42


9.	      BIBLIOGRAPHY                                    43
LIST OF FIGURES
FIGURE 1: SYSTEM ARCHITECTURE……………………………………………….….5
FIGURE 2: USE CASE DIAGRAM FOR DEVELOPER…………………………………...6
FIGURE 3: USE CASE DIAGRAM FOR USER……………………………………….….7
FIGURE 4: ENTITY RELATIONSHIP DIAGRAM………………………………………..8
FIGURE 5: DATABASE ENTRIES OF FRENCH CUISINE…………………………………9
FIGURE 6: DATABASE ENTRIES OF ITALIAN CUISINE…………………………….…..10
FIGURE 7: DATABASE ENTRIES OF MEXICAN CUISINE………………………….……11
FIGURE 8: ANDROID ACTIVITIES…………………………………………………….12
FIGURE 9: ACTIVITY DIAGRAM………………………………………………...……13
FIGURE 10: CLASS DIAGRAM………………………………………………..………14
FIGURE 11: USER VIEWING THE RECIPE……………………………………...………17
Figure 12: Viewing the name of the recipe…………………………………...………17
FIGURE 13: INGREDIENTS OF THE ABOVE RECIPE…………………………...………..18
FIGURE 14: USER ADDING THE RECIPE AS HIS/HER FAVOURITE………………...……18
FIGURE 15: USER CAN VIEW HIS /HER FAVOURITE RECIPE……………………...……19
FIGURE 16:CODE FOR BUILD.GRADEL………………………………………....……………21
FIGURE 17: CODE FOR WIDGET_TEST.DART……………………………………………….….22
FIGURE 18: CODE FOR GRIDLE ANDROID APP…………………………………………….……22
FIGURE 19: CODE FOR LIB MAIN.DART……………………………………………………..….23
FIGURE 20: CODE FOR CHEFS CURATED…………………………………………………….....25
FIGURE 21: CODE FOR INDIAN CUSINES………………………………………………..………30
.


 
LIST OF SCREEN SHOTS

SS 1: APP INTERFACE  (I)...............................................................................21
SS 2: App INTERFACE (II)....................................................................................21
SS 3: APP INTERFACE (III)..............................................................................22
SS 4: APP INTERFACE (IV)……………………………………………………...22



















ABSTRACT

The use of mobile devices has increased significantly in the past decade. All these devices use applications that are created for them. These applications can provide many different services including, social media, music streaming, video streaming, ride sharing, online shopping, and video games. Some of these apps need to be constantly connected to the internet to function properly, while others can work offline. 
This paper presents a food recipe cross-platform application that helps users find and view different food recipes based on different categories, as well as allowing them to search recipes of their comfort using smart search-filters and categories. The users can filter the list of recipes based on the ingredients used in the recipe, the prep time, cook time, and diet. The app aspires to run efficiently, while having an elegant user experience with essential functionalities that of an online application and yet remaining completely offline. 

1. INTRODUCTION

Nowadays, it is safe to admit that the world has attained the form of global village, where everything is accessible through technology. The advent of mobile phone has shaped the life of many people. It is hard to pass a day by without checking and rechecking your social network accounts. This can merely assert that mobile applications has already made their ways to our lives.Research shows that regularly eating home-cooked meals as a family is linked to healthier and happier kids, and teens who are less likely to use alcohol, drugs, or cigarettes. According to Butler, “In recent years, the emergence of smart phones has changed the definition of mobile phones. Phone is no longer just a communication tool, but also an essential part of the people's communication and daily life. Various applications added unlimited fun for people's lives. It is certain that the future of the network will be the mobile terminal.”

Problem statement:

Whether people love to cook or just love to eat, they have a collection of dishes and recipes they'd like to try. Maybe they have a bunch handed down from a loved one. In either case, they certainly need a better method to keep them organized for the long haul than a bunch of index cards in a file folder, which old and tedious. Therefore, cooking with your phone is a lot tastier when you have the right recipes. 

Adults also reap considerable benefits from eating home-cooked meals. Research finds that people who eat home-cooked meals on a regular basis tend to be happier and healthier and consume less sugar and processed foods, which can result in higher energy levels and better mental health. Eating home-cooked meals five or more days a week is even associated with a longer life.

Objectives:

The objective of this project is to develop a “Recetté” mobile application to be used to elevate user kitchen skills, instead of using index cards in a file folder. In other words,Recetté will turn your phone into a pocket sous chef. 

Motivation:

Recetté application is a very useful app for people who love to cook and try out new recipes. It provides user flexibility to search and save recipes from a database and deleting recipe that are no longer required. This application is a time saver providing recipes in few clicks. The interface is clean and simple. It makes use of Flutter containers capability to display options on home screen with image icons. The user can search recipes, view added favourite recipe list all from home screen.





2. LITERATURE SURVEY

Existing System:
Surely there are many recipe apps that offer wide varieties of options to choose from, but most of them are online only and those that are offline lack either that multi-tude of options and devoid of proper UX and structure.
The feasibility study, as its name indicates, aims at assessing the practicality of the proposed project. As stated in the Initial Specifications Report, the objective of this project is to develop a “Recetté” mobile application to be used to elevate user’s kitchen skills and streamline grocery shopping, instead of using index cards in a file folder.

Proposal system:
We are developing an application to help people who are having problems with internet, while retaining all the features that makes an online app great and more features than some existing ones. 
We are using dart and flutter to develop our native app to both iOS, Android, etc...,. Dart/futter allows devs to developed native apps for multiple platforms from a single code base.

Summary:

The goal of this step is to ensure that the requirements are consistent, precise and complete to ensure that we meet the final outcome expectations. There are two types of requirements: functional and non-functional requirements. The functional requirements are the ones that describes the functions of the app; whereas, the non-functional requirements are the ones that present the app constraints and properties.















3. SOFTWARE REQUIRMENTS SPECIFICATIONS

External Interface Requirements:

	Hardware
The mobile app will be operating on Android and iOS.
	Software
The mobile app will be compatible with the mobile and tablet(Android app) last versions.
Developer Requirements:
	Hardware Requirements:

•	OS 	: MacOS-64bit and Windows 7 (64bit) or later
•	HDD	:1.23GB if windows or 2.8GB if MacOS for Flutter SDK
•	RAM	:4GB (minimum) 
•	Processor	: Intel i3 3rdgen or AMD equivalent 

	Software Requirements:

•	OS 	: MacOS-64bit and Windows 7 (64bit) or later
•	Tools            	: Flutter SDK
•	Android Studio/Visual Studio Code or any other IDE supporting dart
•	Git
•	Windows Powershell 5.0(only for windows users)

	User Requirements:

•	OS	: Android Jellybean or newer and iOS 8 or newer
•	Hardware	: iOS devices (iPhone 4s or newer) and ARM android devices
•	Storage Space   : ~200MB
•	RAM	: 2GB






Non-Functional Requirements:

Non-functional analysis contains about the application analysis of the user's interest level. In
this section will explain how the application is tested in such a way and get the user's assessment
of the appropriateness and condition of the application.

•	Security:
The data within the application must be protected from tampering.
•	Availability:
The application will must available to the user without internet connection at all times.
•	Usability:
It has good UX/UI with elegant design and enough information to allow the user to fully use the application.
•	Performance:
The application must be responsive and should match the refresh-rate of the screen.

	Product Requirements:
•	Usability Requirements: 
-	The application shall be easy to use and intuitive. 
-	The application shall have a user-friendly interface. 
-	GUI shall be simple and clear. 
•	Performance Requirements:
-	The application shall be fast and robust when loading. 
-	The program shall not allow more than 10 min/year of failure. 
•	Space Requirements: 
-	The application shall have enough memory space in order to store high number of data. 
•	Reliability Requirements: 
-	The application shall not produce an incorrect output. 
•	Portability Requirements: 
-	The software shall work in all different platforms.
-	 
	Organizational Requirements:
•	Implementation Requirements: 
-The application shall be implemented using Android Studio.

	External Requirements:
•	Inter-operability Requirements. 
- The application shall allow access to the different department of the application without altering its efficiency and consistency. 
•	Ethical Requirements: 
          - The application shall be license free.

# 4. SYSTEM DESIGN

## System Architecture:

**Figure 1: System architecture**

System architecture describes the organization of the system in terms of structure and behavior by representing the different components and the relationship between them. The architecture of this system is composed of a mobile device (iOS/Android) that allows the users to make use of the application and its different functionalities of the system.  
The Database is part of the application and is composed of various lists of dictionaries. Whenever the user sends a request, the application sends the appropriate parameters based on the request to `List_builder` that generates the appropriate response by making use of the database.

## Use Case Diagrams:

### a. Use case diagram for developer:

**Figure 2: Use Case Diagram for Developer**

### b. Use case diagram for User:

**Figure 3: Use Case Diagram for User**

## Entity Relationship Diagram:

This flowchart illustrates how "entities" such as Users, objects, or concepts relate to each other within a system. They mirror grammatical structure, with entities as nouns and relationships as verbs.

**Figure 4: Entity Relationship Diagram**  

### Database Entries:

- **Figure 5**: Database entries of French cuisine
- **Figure 6**: Database entries of Italian cuisine
- **Figure 7**: Database entries of Mexican cuisine

## Android Application Design:

The Android user interface is built around `Activities`, which are single focused things that a user can do. They are directly related to the functional requirement defined for the application. The following activities are derived from the user requirements and should be implemented to fulfill the functional requirements.

**Figure 8: Android Activities**

## Activity Diagram:

This is another important behavioral diagram in UML to describe dynamic aspects of the system. It is essentially an advanced version of a flow chart that models the flow from one activity to another.

**Figure 9: Activity Diagram**

## Class Diagram:

Class diagrams are the main building block in object-oriented modeling. They are used to show the different objects in a system, their attributes, their operations, and the relationships among them. In our example, "recipes" are depicted.

**Figure 10: Class Diagram**

# 5. IMPLEMENTATION

## Environmental Setup:
1. Setting up 'Environment' for application
2. Flutter Setup

## System Requirements:

To install and run Flutter, your development environment must meet these minimum requirements:
- Operating Systems: Windows 7 SP1 or later (64-bit), x86-64 based
- Disk Space: 1.32 GB (does not include disk space for IDE/tools)
- Tools: Flutter depends on these tools being available in your environment.
  - Windows PowerShell 5.0 or newer (pre-installed with Windows 10)
  - Git for Windows 2.x, with the Use Git from the Windows Command Prompt option.

If Git for Windows is already installed, make sure you can run git commands from the command prompt or PowerShell.

### Get the Flutter SDK:

1. Download the latest stable release of the Flutter SDK: `flutter_windows_1.22.5-stable.zip`.  
   For other release channels and older builds, see the SDK releases page.
2. Extract the zip file and place the contained flutter in the desired installation location (e.g., `C:\src\flutter`).

**Warning:** Do not install Flutter in a directory like `C:\Program Files\` that requires elevated privileges.  
You are now ready to run Flutter commands in the Flutter Console.

### Update your PATH:

To run Flutter commands in the regular Windows console:
1. From the Start search bar, enter 'env' and select Edit environment variables for your account.
2. Under User variables:
   - If an entry called `Path` exists, append the full path to `flutter\bin` using `;` as a separator.
   - If the entry doesn’t exist, create a new user variable named `Path` with the full path to `flutter\bin` as its value.

You have to close and reopen any existing console windows for these changes to take effect.

### Run Flutter Doctor:

From a console window that has the Flutter directory in the path, run the following command to check for any platform dependencies:

```bash
C:\src\flutter>flutter doctor
```
# Module Description

The implementation took roughly three months and involved coding every single day to arrive at the final product. It focused on designing activities, similar to pages in web applications, and linking the graphical user interface with the functionalities. Every time we implemented a feature, we tested it directly on the AVD emulator and my Android phone to get a real-life representation of how the app would look on clients’ mobile phones. We also ensured compatibility with phones supporting different Android versions. 

The mobile application has the following features:

## 1. Smart Search-Filters:
Users can search or filter recipes by name, base ingredients, and diet. When a user searches for an ingredient, all related recipes will be shown, and searches based on diet are also available. For example, users allergic to certain ingredients can exclude them from meal plans. The search filter returns recipes depending on the type of search.

## 2. Categorized View:
All recipes are categorized into cuisines, food types, diets, and varieties. We collected authentic recipes from various countries, categorizing them based on food type, specific diets, and user preferences.

## 3. Curated Collections:
We gathered recipes from famous chefs worldwide, listing their signature dishes and collecting data from popular websites and articles.

## 4. Pantry Manager:
Users can manage their personal pantry with the help of the pantry manager, included in our application.

## 5. Meal Planner:
For busy people, our meal planner helps plan and prep meals in advance. It assists users in preparing nutritious meals and allows them to plan ahead for special events, with a reminder system to notify them.

## 6. Shopping List:
Users can add ingredients to a shopping list, tracking missing items for later purchase. The feature integrates with smartwatches, allows sharing of virtual lists, and provides nutritional information.

## 7. Skill Guide and Glossary:
The skill guide provides users with cooking techniques (e.g., knife skills) and a glossary of culinary terminology, especially helpful for beginners who may lack cooking knowledge.

## Friendly and Flexible GUI:
The app features a user-friendly GUI. We used Picasso as an image loader and ensured that every layout is scrollable. For design, I used Photoshop for buttons, layouts, and backgrounds.

## Recipe Viewing Features:

### View Recipe:
Users can view recipes, accessing the Recipe Forum where recipes are listed by creation date. Recipes are displayed with images, titles, and cooking directions.

### Search for a Recipe:
Registered users can search for a recipe by title. This shortcut allows users to quickly find targeted recipes if they have been posted before.

### View Ingredients:
Users can view ingredients of a recipe and mark them as needed, adding them to the shopping list.

### Add Recipe as Favorite:
Users can mark a recipe as a favorite. Each recipe in the search results has a favorite button (heart icon) that allows users to save it.

### View My Favorite Recipes:
Users can access the recipes they’ve marked as favorite.

---

# Software Description

Choosing the right technology enablers is essential for the application’s success. We followed the principle that there’s no "best" technology, but rather suitable ones, and used existing solutions where possible.

## Android Studio:
- **Android Studio** is the official IDE for Android development, designed to help build high-quality apps for Android devices. It offers tools specifically tailored for Android developers, including rich code editing, debugging, testing, and profiling tools.
  
### Reasons for Choosing Android Studio:
- **Instant Run**: Pushes code and resource changes to the running app without restarting it, allowing you to see changes immediately.
- **Intelligent Code Editor**: Offers advanced code completion, refactoring, and code analysis to improve productivity.
- **Optimized for All Android Devices**: Provides a unified environment for building apps for phones, tablets, Android Wear, TV, and Auto.

## Android Virtual Device (AVD):
The AVD emulator can be used instead of physical Android devices, offering a development experience as good as or better than actual devices.

## Notepad++:
Notepad++ is a free source code editor that supports multiple languages and serves as a replacement for Notepad.

### SIMPLE CODE:
```groovy
def localProperties = new Properties ()
def localPropertiesFile = rootProject.file('local.properties')
if (localPropertiesFile.exists()) {
    localPropertiesFile.withReader('UTF-8') { reader ->
        localProperties.load(reader)
    }
}

def flutterRoot = localProperties.getProperty('flutter.sdk')
if (flutterRoot == null) {
    throw new GradleException("Flutter SDK not found. Define location with flutter.sdk in the local.properties file.")
}

def flutterVersionCode = localProperties.getProperty('flutter.versionCode')
if (flutterVersionCode == null) {
    flutterVersionCode = '1'
}
def flutterVersionName = localProperties.getProperty('flutter.versionName')
if (flutterVersionName == null) {
    flutterVersionName = '1.0'
}
apply plugin: 'com.android.application'
apply plugin: 'kotlin-android'
apply from: "$flutterRoot/packages/flutter_tools/gradle/flutter.gradle"

android {
    compileSdkVersion 28

    sourceSets {
        main.java.srcDirs += 'src/main/kotlin'
    }

    lintOptions {
        disable 'InvalidPackage'
    }
    defaultConfig {
        // TODO: Specify your own unique Application ID (https://developer.android.com/studio/build/application-id.html).
        applicationId "com.hollsinthesun.cookbook"
        minSdkVersion 16
        targetSdkVersion 28
        versionCode flutterVersionCode.toInteger()
        versionName flutterVersionName
    }
    buildTypes {
        release {
            // TODO: Add your own signing config for the release build.
            // Signing with the debug keys for now, so `flutter run --release` works.
            signingConfig signingConfigs.debug
        }
    }
flutter {
    source '../..'
}
dependencies {
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
}
```
# Indian Cuisines

## 1. Hyderabadi Dum Biryani

- **Serves:** 6
- **Prep Time:** 2 hours 45 mins
- **Cook Time:** 45 mins

### Ingredients

**For Chicken Marination:**
- 1 1/2 kg chicken cut into large pieces
- 2 tbsp ginger garlic paste
- 2 tbsp red chilli powder
- 1 tsp turmeric powder
- Salt as per taste
- 1 bunch coriander leaves
- 1 bunch mint leaves
- 7-8 green chillies
- 1 tsp caraway seeds (shahi zeera)
- 3-4 cloves (loung)
- 2 cinnamon sticks (dalchini)
- 3-4 cardamoms (elaichi)
- 3-4 black pepper corns (kali mirch)
- 2 cups fried golden brown onions
- 2 cups yogurt
- 1 tbsp oil
- 1 tbsp lemon juice
- 1 tsp garam masala powder

**For the Rice:**
- Water for boiling
- 1 kg basmati rice
- 2-3 cloves (loung)
- 1 cinnamon stick (dalchini)
- 2-3 cardamoms (elaichi)
- 1 tsp caraway seeds (shahi zeera)
- 2-3 black pepper corns (kali mirch)
- 1 tbsp lemon juice
- Salt to taste

**For Dum Seasoning:**
- 2 tbsp oil
- 2 tbsp coriander leaves
- 2 tbsp mint leaves
- 2 tbsp fried onions
- 1 tbsp lemon juice
- 1 cup saffron flavored milk
- 1 tbsp ghee
- 1 cup water

**For Garnishing:**
- Fried onions

### Process

**For The Chicken Marination:**
1. Wash the chicken pieces well with lemon juice and water and strain the chicken completely.
2. Add ginger garlic paste into the chicken.
3. Add red chilli powder, turmeric powder, and salt. Mix well.
4. In a blender, add a bunch of coriander leaves, a bunch of mint leaves, green chillies, and a pinch of salt. Blend to make a green paste or hara masala paste.
5. Add the green paste to the chicken marinade.
6. Add whole garam masala (cardamom, cinnamon, cloves, black pepper corns, caraway seeds).
7. Mix the entire mixture well.
8. Crush the fried onions and add them into the marinade.
9. Add beaten yogurt and mix well.
10. Add oil over the marinade and mix thoroughly.
11. Add garam masala powder and lemon juice. Mix well.
12. Adjust salt as needed.
13. Refrigerate the marinade for about 45 mins to 1 hour.

**Procedure To Cook The Rice:**
1. Wash the basmati rice and soak it for about 35 mins.
2. In a cooking pot, add water generously.
3. Add salt, cinnamon stick, cloves, shahi zeera, black pepper corns, and cardamoms to the water.
4. Bring the water to a boil.
5. Add the soaked rice to the boiling water.
6. Cook the rice for about 6-7 mins until it is three-fourths done.
7. Strain the rice completely and set aside.

**Procedure To Give The Dum:**
1. In a cooking pot, add oil to the base and spread it evenly.
2. Add the chicken marinade and spread it evenly.
3. Add the cooked rice to the marinade.
4. Spread the rice evenly over the marinade.
5. Season the rice with coriander leaves, mint leaves, and fried onions.
6. Add lemon juice over the rice.
7. Add saffron flavored milk (2 saffron strands in 1/4 cup milk) for color.
8. Add ghee.
9. Add a little water if necessary (optional).
10. Make a chapathi dough and seal the lid and the cooking pot tightly with the dough.
11. Turn on the flame and place the cooking pot on the flame.
12. Dum the biryani on a simmer flame for about 45 mins.

---

## 2. Chicken Makhani (Indian Butter Chicken)

- **Serves:** 4
- **Prep Time:** 10 mins
- **Cook Time:** 25 mins

### Ingredients

**For the Sauce:**
- 1 tablespoon peanut oil
- 1 shallot, finely chopped
- 1/4 white onion, chopped
- 2 tablespoons butter
- 2 teaspoons lemon juice
- 1 tablespoon ginger garlic paste
- 1 teaspoon garam masala
- 1 teaspoon chili powder
- 1 teaspoon ground cumin
- 1 bay leaf
- 1/4 cup plain yogurt
- 1 cup half-and-half
- 1 cup tomato puree
- 1/4 teaspoon cayenne pepper (to taste)
- 1 pinch salt
- 1 pinch black pepper

**For the Chicken:**
- 1 tablespoon peanut oil
- 1 pound boneless, skinless chicken thighs, cut into bite-size pieces
- 1 teaspoon garam masala
- 1 pinch cayenne pepper
- 1 tablespoon cornstarch
- 1/4 cup water

### Process

**Step 1:**
1. Heat 1 tablespoon oil in a large saucepan over medium-high heat.
2. Sauté shallot and onion until soft and translucent.
3. Stir in butter, lemon juice, ginger-garlic paste, 1 teaspoon garam masala, chili powder, cumin, and bay leaf.
4. Cook, stirring, for 1 minute.
5. Add tomato sauce and cook for 2 minutes, stirring frequently.
6. Stir in half-and-half and yogurt. Reduce heat to low and simmer for 10 mins, stirring frequently.
7. Season with salt and pepper. Remove from heat and set aside.

**Step 2:**
1. Heat 1 tablespoon oil in a large heavy skillet over medium heat.
2. Cook chicken until lightly browned, about 10 mins.
3. Reduce heat and season with 1 teaspoon garam masala and cayenne.
4. Stir in a few spoonfuls of sauce and simmer until the liquid has reduced and the chicken is no longer pink.
5. Stir the cooked chicken into the sauce.

**Step 3:**
1. Mix together cornstarch and water, then stir into the sauce.
2. Cook for 5 to 10 mins, or until thickened.

---

## 3. Bisi Bela Bath

- **Serves:** 3
- **Prep Time:** 10 mins
- **Cook Time:** 30 mins

### Ingredients

**Bisi Bele Bath Masala:**
- 4 tsp coriander seeds
- 4 tsp chana dal
- 2 tsp urad dal
- 1 tsp jeera (cumin)
- 1/4 tsp methi (fenugreek seeds)
- 1/2 tsp pepper
- 3 pods cardamom
- 1 inch cinnamon stick (dalchini)
- 4 cloves (lavang)
- 2 tbsp dry coconut (copra)
- 2 tsp poppy seeds (khus khus)
- 1 tsp sesame seeds (til)
- 1 tsp oil
- 12 dried Kashmiri red chillies
- Few curry leaves
- Pinch of hing (asafoetida)

**Other Ingredients:**
- 1/2 carrot, chopped
- 5 beans, chopped
- 2 tbsp matar (peas)
- 1/2 potato (aloo), cubed
- 2 tbsp peanuts
- 2 cups water
- 1/4 tsp turmeric (haldi)
- 1 1/2 tsp salt
- 3/4 cup tamarind extract
- 1/2 tsp jaggery (gud)
- 1/2 onions, petals
- 1 cup toor dal, cooked
- 2 1/2 cups rice, cooked
- 1 cup water
- 1 tbsp ghee (clarified butter)

### Process

1. **Cook the Vegetables:**
   - Cook vegetables, 2 tbsp peanuts, 2 cups water, 1/4 tsp turmeric, and 1 tsp salt.

2. **Add Tamarind and Jaggery:**
   - Add 3/4 cup tamarind extract, 1/2 tsp jaggery, and 1/2 onions. Boil for 10 mins.

3. **Combine with Dal and Rice:**
   - Add 1 cup of cooked toor dal, 2 1/2 cups of cooked rice, and 1 cup water.
   - Add 4 tsp of bisi bisi bele bath masala and simmer for 20 mins.

4. **Add Tempering:**
   - Pour the tempering over the bisi bele bath and serve with boodi or mixture.

---

## 4. Matar Paneer

- **Serves:** 4
- **Prep Time:** 10 mins
- **Cook Time:** 30 mins

### Ingredients

**For Onion Tomato Paste:**
- 2 tbsp oil
- 1 onion, sliced
- 3 cloves garlic, chopped
- 1 inch ginger
- 3 tomatoes, sliced

**Other Ingredients:**
- 2 tbsp oil
- 1 bay leaf
- 1 inch cinnamon stick
- 2 pods cardamom
- 1 tsp cumin (jeera)
- 1/4 tsp turmeric
- 1 tsp Kashmiri red chilli powder
- 1 tbsp besan (gram flour)
- 1/4 tsp cumin powder
- 1 tsp coriander powder
- 1 tsp salt
- 1 cup water
- 1 cup peas (matar)
- 12 cubes paneer (cottage cheese)
- 2 tbsp coriander, finely chopped
- 1/4 tsp garam masala
- 1 tsp kasuri methi

### Process

1. **Prepare the Paste:**
   - In a large kadai, heat 2 tbsp oil and sauté spices.
   - Add 1/4 tsp turmeric, 1 tsp chilli powder, and 1 tbsp besan. Roast well.
   - Add the prepared onion tomato paste and sauté thoroughly.

2. **Add Spices and Water:**
   - Add 1/4 tsp cumin powder, 1 tsp coriander powder, and 1 tsp salt.
   - Add 1 cup water and stir well.
   - Add 1 cup peas and stir. Cover and cook for 10 mins.

3. **Add Paneer:**
   - Add 12 cubes paneer and simmer for 10 mins.

4. **Final Touches:**
   - Add 2 tbsp coriander, 1/4 tsp garam masala, and 1 tsp kasuri methi.
   - Mix well and enjoy with roti or rice.

---

## 5. Tandoori Chicken

- **Serves:** 21 pieces
- **Prep Time:** 30 mins
- **Cook Time:** 12 mins

### Ingredients

- 3 tbsp vegetable oil
- 1 teaspoon ground coriander
- 1 teaspoon ground cumin
- 1 teaspoon ground turmeric
- 1 teaspoon cayenne
- 1 tbsp garam masala
- 1 tbsp sweet (not hot) paprika
- 1 cup plain yogurt (can substitute buttermilk)
- 2 tbsp lemon juice
- 4 minced garlic cloves
- 2 tbsp minced fresh ginger
- 1 teaspoon salt
- 4 whole chicken legs (drumsticks and thighs), or equivalent, skinless, bone-in

### Process

1. **Heat the Spices:**
   - Heat oil in a small pan over medium heat.
   - Cook coriander, cumin, turmeric, cayenne, garam masala, and paprika, stirring often until fragrant (2-3 mins).
   - Let the spice-oil mixture cool completely.

2. **Prepare the Marinade:**
   - Whisk the cooled spice-oil mixture into the yogurt.
   - Mix in lemon juice, garlic, salt, and ginger.

3. **Marinate the Chicken:**
   - Cut deep slashes into the chicken pieces (2-3 cuts per piece).
   - Coat the chicken in the marinade.
   - Cover and chill for at least 1 hour (preferably 6 hours), no more than 8 hours.

4. **Prepare the Grill:**
   - Preheat the grill with one side hot (direct heat) and the other side cooler (indirect heat).
   - Wipe the grill grates with a paper towel soaked in vegetable oil.

5. **Cook the Chicken:**
   - Shake off excess marinade and place the chicken on the hot side of the grill.
   - Cook for 2-3 mins, turning to brown on all sides.
   - Move to the cooler side, cover, and cook for 20-40 mins until juices run clear.

6. **Serve:**
   - Let the chicken rest for at least 5 mins before serving.
   - Serve with naan, Indian flatbread, or rice with yogurt-based raita.

---

## 6. Masala Dosa

- **Serves:** 6
- **Prep Time:** 20 mins
- **Cook Time:** 45 mins

### Ingredients

**For Batter:**
- 3 cups sona masuri rice
- 1/2 tsp methi (fenugreek seeds)
- Water for soaking
- 1 cup urad dal
- 2 tbsp toor dal
- 2 tbsp chana dal
- 1 cup poha (avalakki), rinsed

**For Aloo Bhaji:**
- 2 tbsp oil
- 1 tsp mustard
- 1 tsp urad dal
- 1 tsp chana dal
- 1 dried red chilli
- Few curry leaves
- Pinch hing (asafoetida)
- 2 chillies, finely chopped
- 1 inch ginger, finely chopped
- 1 onion, sliced
- 1/4 tsp turmeric
- 1 tsp salt
- 3 potatoes, boiled & mashed
- 2 tbsp coriander, finely chopped
- 2 tbsp lemon juice

### Process

**Masala Dosa Batter Preparation:**
1. In a large bowl, combine 3 cups sona masuri rice and 1/2 tsp methi. Rinse well and soak in water for 4 hours.
2. In another bowl, combine 1 cup urad dal, 2 tbsp toor dal, and 2 tbsp chana dal. Rinse well and soak in water for 2 hours.
3. After soaking, drain the water and transfer the dals to a grinder. Blend to a smooth paste with water as required.
4. Scrape the sides. The smooth and fluffy batter will be ready after 40 mins. Transfer to a large vessel and set aside.
5. In the same grinder, add soaked rice and 1 cup rinsed poha. Blend to a coarse paste with water.
6. Transfer the rice batter to the urad dal batter. Mix well to combine thoroughly.
7. Ferment in a warm place for at least 8 hours or until the batter doubles in volume. In cold climates, place the batter in a warm oven (slightly warm and then turn off) to ferment.
8. Once fermented, mix gently without disturbing air pockets.
9. Transfer 4 cups of fermented batter to a small bowl and add 1 tsp salt. Mix well until combined. Keep aside.

**Aloo Bhaji Preparation:**
1. In a large kadai, heat 2 tbsp oil and splutter 1 tsp mustard, 1 tsp urad dal, 1 tsp chana dal, 1 dried red chilli, a few curry leaves, and a pinch of hing.
2. Add 2 chillies and 1 inch ginger. Sauté well.
3. Add 1 onion and sauté until onions shrink slightly.
4. Add 1/4 tsp turmeric and 1 tsp salt. Sauté well.
5. Add 3 boiled and mashed potatoes. Mix well, mashing slightly to combine thoroughly.
6. Turn off the flame and add 2 tbsp coriander and 2 tbsp lemon juice. Mix well. Aloo bhaji is ready. Keep aside.

**Masala Dosa Preparation:**
1. Heat a ladleful of batter on a hot tawa (griddle).
2. Spread the batter as thin as possible to make a crispy dosa.
3. Take 1 tsp of butter and spread it uniformly.
4. Place 2 tbsp of prepared aloo masala in the center.
5. Roast until the dosa turns golden brown and crisp.
6. Scrape the sides of the dosa and roll it.
7. Serve with coconut chutney and sambar.

---

## 7. Rogan Josh

- **Serves:** 6
- **Prep Time:** 10 mins
- **Cook Time:** 45 mins

### Ingredients

- 1 kg meat
- 1 cup mustard/refined oil
- 3 tsp red chili powder
- 3 tsp fennel powder
- 2 tsp ginger powder
- 2 tsp cumin powder
- 3 tsp brown cardamom powder
- 1 tsp asafoetida
- 4 green cardamoms
- 2 cinnamon sticks
- 2 bay leaves
- 2 cloves
- 1/3 tsp saffron (optional)
- 1 cup curd
- Pinch of salt

### Process

1. **Prepare the Meat:**
   - Wash the meat properly.
   - Heat oil in a pressure cooker.
   - Add cinnamon, bay leaves, green cardamom, cloves, a teaspoon of salt, asafoetida, and meat.
   - Fry the meat until it turns brown.
   - Once browned, pour a cup of water.
   
2. **Add Spices:**
   - Add red chili powder and saffron to the meat.
   - Stir for about a minute.
   
3. **Add Curd:**
   - Mix the curd nicely and pour it into the pressure cooker.
   - Stir continuously until the mixture gains a reddish tinge.
   
4. **Cook:**
   - Add 2 cups of water, fennel powder, ginger powder.
   - Pressure cook for 2 minutes.
   
5. **Final Touches:**
   - Check if the meat is tender.
   - Peel and grind green and brown cardamom. Add to the meat dish.
   - Sprinkle cumin powder and simmer for a minute.
   
6. **Serve:**
   - Serve hot with rice or naan.

---

## 8. Pongal

- **Serves:** 2
- **Prep Time:** 5 mins
- **Cook Time:** 20 mins

### Ingredients

**For Pressure Cooking:**
- 1 tsp ghee (clarified butter)
- 1/2 cup rice, rinsed
- 1/2 cup moong dal, rinsed
- 4 cups water
- 1/2 tsp salt

**For Tempering:**
- 2 tbsp ghee (clarified butter)
- 1 tsp cumin (jeera)
- 1/2 tsp crushed pepper
- 1 inch ginger, finely chopped
- 2 chillies, slit
- 10 cashews (kaju), halves
- Pinch of hing (asafoetida)

### Process

1. **Cook the Rice and Dal:**
   - In a pressure cooker, heat 1 tsp ghee.
   - Add 1/2 cup rice and 1/2 cup moong dal. Sauté for a minute until aromatic.
   - Add 4 cups water and 1/2 tsp salt. Mix well.
   - Cover and pressure cook for 5 whistles on medium flame.
   - Once pressure settles, open the cooker and mix well.

2. **Prepare the Tempering:**
   - In a pan, heat 2 tbsp ghee.
   - Add 1 tsp cumin, 1/2 tsp crushed pepper, 1 inch ginger, 2 chillies, 10 cashews, and a pinch of hing.
   - Sauté on low flame until cashews turn golden brown.

3. **Combine:**
   - Pour the tempering over the cooked rice and dal mixture.
   - Mix well, adding more ghee if required.

4. **Serve:**
   - Serve ven pongal/khara pongal with coconut chutney and sambar.

---

## 9. Dhokla

- **Serves:** 21 pieces
- **Prep Time:** 30 mins
- **Cook Time:** 12 mins

### Ingredients

**For Rava Dhokla:**
- 1 cup rava (bombay rava / semolina / sooji)
- 1 cup thick curd/yogurt, slightly sour
- 1/2 tsp sugar
- 1 tsp grated ginger (adrak)
- 1 tsp chili paste
- 2 tsp oil
- Salt to taste
- 1/4 cup water (or as required)
- 1 tsp eno fruit salt or 3/4 tsp baking soda

**For Tempering:**
- 2 tsp oil
- 1 tsp mustard seeds (rai)
- 1/2 tsp cumin seeds (jeera)
- 1/2 tsp sesame seeds (til)
- Pinch of hing (asafoetida)
- Few curry leaves
- 2 green chillies, slit
- 2 tbsp coriander leaves, finely chopped

### Process

1. **Prepare the Batter:**
   - In a large mixing bowl, combine rava and curd.
   - Add sugar, grated ginger, chili paste, and salt.
   - Mix well to form a thick batter.
   - Rest for 30 mins or until rava absorbs moisture.
   - Add water as required and mix well to achieve an idli batter consistency.
   - Add eno fruit salt and mix gently until the batter turns frothy.
   - Transfer the batter to a greased plate.

2. **Steam the Dhokla:**
   - Steam the dhokla batter for 12 mins.

3. **Prepare the Tempering:**
   - Heat oil in a pan.
   - Add mustard seeds, cumin seeds, sesame seeds, and hing.
   - Once mustard seeds splutter, add curry leaves and green chillies.
   - Sauté for a while until the tempering splutters.

4. **Finalize:**
   - Spread the tempering over the steamed dhokla.
   - Sprinkle finely chopped coriander leaves.
   - Cut the dhokla into desired shapes.
   - Serve soft and spongy rava dhokla with green chutney.

---

## 10. Chettinad Fish Curry

- **Serves:** 4-5
- **Prep Time:** 10 mins
- **Cook Time:** 45 mins

### Ingredients

- 1/2 kg fish (Paarai fish)
- 1 tblspn oil
- 1 tsp mustard seeds (kaduku)
- 1 small onion, finely chopped
- 1 large tomato, cut into long slices
- A sprig of curry leaves
- 2 tblspn coriander leaves, finely chopped
- 3 tblspn tamarind pulp
- **For Sauteing and Grinding:**
  - 1 tblspn oil
  - 1 tblspn fennel seeds (saunf / sombu)
  - 1 large sliced onion
  - 1 tblspn garlic paste
  - 1 large chopped tomato
  - 1 tblspn chilli powder (to taste)
  - 2 tblspn coriander powder
  - 1 tsp turmeric powder (manjal podi)
  - 1/2 cup grated coconut

### Process

1. **Prepare the Masala:**
   - Heat oil in an earthenware kadai.
   - Add fennel seeds and sauté for a minute.
   - Add onions and sauté for another minute.
   - Add garlic and sauté for 30 seconds.
   - Add tomatoes and sauté well.
   - Add chilli powder, coriander powder, and turmeric powder. Sauté for a minute.
   - Add grated coconut and mix well.
   - Transfer the mixture to a blender and puree until smooth.

2. **Cook the Curry:**
   - In the same kadai, heat oil.
   - Add mustard seeds and let them crackle.
   - Add chopped onions and curry leaves. Sauté until golden.
   - Add the coconut masala and cook until oil separates.
   - Add the long-sliced tomatoes and toss well.
   - Add tamarind pulp and some water. Mix well and bring to a boil.
   - Add fish pieces and mix well.
   - Season with salt.
   - Simmer for 8-10 mins until the fish is cooked.
   - Add coriander leaves and mix well.
   
3. **Serve:**
   - Serve with rice.

---

## 11. Chettinad Fish Curry

*Note: It appears that "Chettinad Fish Curry" is listed twice with the same name but different details. Please ensure each recipe has a unique name to avoid confusion.*

---

Feel free to add more recipes following the same structure!

# 6. SYSTEM TESTING

## Tests:
The app development will consist of five parts. The first part will be devoted to data gathering and software requirements specification. Consequently, I will have a look at different mobile apps which target the same goal. They are plenty of Recipe Organizer apps. Each one has some various features. The second part will be dedicated to the design phase, including the app and the database. Also, in this phase, the software tools to be used will be specified. For example, the IDE, the database, the modelling language for the design, and finally the software testing tools. The third part will be the implementation phase, here, the design will be converted to code in order to develop the targeted app. The fourth step will be devoted to testing the app. In this phase, two testing methods will be used, namely: Black Box testing and White box testing. The last phase will be the deployment phase.

- Recipes are categorized in the form of cuisines (based on countries and origin).
- Fast food items are categorized into Burgers, Pizza, Noodles and Sausages.
- We have also collected the signature dishes of some of the world-famous chefs under Chefs Curated category.
- We have a category named ‘Meals’, where further divided into 6 categories:
  - Lunch
  - Breakfast
  - Dessert
  - Dinner
  - Salad
  - Soups
- We also have a special Category. Here, the user specific recipes are collected. For instance collection of vegan recipes are included.

# 8. CONCLUSION

The Recetté application meets with the enterprise class application principles. It is designed to be performing, scalable, extensible and highly available. Given that it may be improved in many ways, the application is also easily maintainable.

This document summarizes the work that has been done since the beginning of this semester. Indeed, it starts by giving an overview about the project specification and requirements. The document also states the methodology followed and which consists of 5 main parts:

The first part will be devoted to data gathering and software requirements specification. Consequently, I will have a look at different mobile apps which target the same goal. They are plenty of Cookbook apps. Each one has some various features.

The second part will be dedicated to the design phase, including the app and the database. Also, in this phase, the software tools to be used will be specified. For example, the IDE, the modelling language for the design, and finally the software testing tools.

The third part will be the implementation phase, here, the design will be converted to code in order to develop the targeted app. The last phase will be the deployment phase.

# 9. BIBLIOGRAPHY

1. flutter_svg | Flutter Package (pub.dev)
2. Recipes | Recipes for Breakfast, Lunch & Dinner (delicious.com.au)
3. Meal and Recipe Finder: cooking instructions to bake healthy food (allthemeals.com)
4. Cookbook - Flutter

