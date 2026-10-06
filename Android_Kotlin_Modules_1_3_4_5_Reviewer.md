# Android Studio Kotlin Mobile Programming --- Reviewer

## Module 1 --- Android Introduction, Versions, and Architecture

### 1. Android 4.4 is also known as \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

-   Pie
-   Marshmallow
-   Nougat
-   KitKat

**Correct Answer:** KitKat

### 2. The first release of Android with a dessert codename is \_\_\_\_\_\_\_\_\_\_\_.

-   Android 1.2
-   Android 1.0
-   Android 1.8
-   Android 1.5

**Correct Answer:** Android 1.5

### 3. Multi-window support was introduced in Android \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

-   KitKat
-   Nougat
-   Marshmallow
-   Pie

**Correct Answer:** Nougat

### 4. The top layer of the Android architecture is \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_. The native and third-party applications like contacts, email, music, gallery, clock, games, etc. whatever we will build those will be installed on this layer only.

-   Application Framework
-   Applications
-   Platform Libraries
-   Android Runtime

**Correct Answer:** Applications

### 5. The Dalvik VM enables every Android application to run in its own process, with its own instance of the Dalvik virtual machine.

-   True
-   False

**Correct Answer:** True

### 6. In Android architecture, Activity Manager falls under \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_.

-   Android Runtime
-   Application Framework
-   Linux Kernel
-   Applications

**Correct Answer:** Application Framework

### 7. Android is proprietary and only Google is allowed to use it.

-   True
-   False

**Correct Answer:** False

### 8. Android is a mobile operating system based on Windows.

-   True
-   False

**Correct Answer:** False

### 9. Google purchased Android in what year?

-   1999
-   2005
-   2001
-   2012

**Correct Answer:** 2005

### 10. One of the major updates on Android Pie is \_\_\_\_\_\_\_\_\_\_\_\_\_\_.

-   Material Design
-   PIP Mode
-   Fingerprint Authentication
-   Adaptive Brightness

**Correct Answer:** Adaptive Brightness

------------------------------------------------------------------------

## Module 3 --- Kotlin Basics

### 1. What is a correct syntax to output "Hello World" in Kotlin?

-   `cout<<"Hello Gwapo";`
-   `println("Hello Gwapo")`
-   `Console.WriteLine("Hello Gwapo");`
-   `System.out.println("Hello Gwapo");`

**Correct Answer:** `println("Hello Gwapo")`

### 2. What is the correct way to create an object called myObj of the class MyClass?

-   `val myObj = MyClass()`
-   `MyClass.new myObj`
-   `myObj : MyClass()`
-   `myObj = new MyClass()`

**Correct Answer:** `val myObj = MyClass()`

### 3. In Kotlin, code statements must end with a semicolon (;).

-   True
-   False

**Correct Answer:** False

### 4. In Kotlin, how can you create a variable with the numeric value 5?

-   `num =. 5`
-   `num = 5 int`
-   `val num = 5`
-   `int num = 5`

**Correct Answer:** `val num = 5`

### 5. How do you insert COMMENTS in Kotlin code?

-   `// this is my comment`
-   `-- this is my comment`
-   `% this is my comment`
-   `# this is my comment`

**Correct Answer:** `// this is my comment`

### 6. In Kotlin, array indexes start with:

-   -1
-   0
-   nil
-   1

**Correct Answer:** 0

### 7. Type the keyword that is used to declare a function in Kotlin below:

**Correct Answer:** `fun`

### 8. Which of the following is used to declare an array in Kotlin?

-   `array()`
-   `arrayOf()`
-   `new array()`
-   `[]`

**Correct Answer:** `arrayOf()`

### 9. What is the fname known as in the following code: `fun myFunction(fname: String)`

-   override
-   inherit
-   parameter
-   range

**Correct Answer:** parameter

### 10. What is the output of the following code: `println(5 > 3 && 5 < 10)`

-   true
-   null
-   undefined
-   false

**Correct Answer:** true

### 11. In Kotlin, it is possible to inherit class properties and functions from one class to another.

-   True
-   False

**Correct Answer:** True

------------------------------------------------------------------------

## Module 4 --- Android Components and Resources

### 1. This application component dictates the UI and handles the user interaction to the smart phone screen.

-   Activities
-   Broadcast Receivers
-   Services
-   Content Providers

**Correct Answer:** Activities

### 2. We can create an array of values using XML and use it depending on our application needs.

-   True
-   False

**Correct Answer:** True

### 3. A service is a component that runs in the background to perform long-running operations.

-   True
-   False

**Correct Answer:** True

### 4. Consider the given resources below:

``` xml
<resources>
    <color name="blue">#2196f3</color>
    <string name="myapp">MyApp</string>
</resources>
```

How will you access the color resource in your Java file? -
`@color/blue` - `R.color.blue` - `R.id.blue` - `@+id/blue`

**Correct Answer:** `R.color.blue`

### 5. All application components in an Android application can be observed in the MainActivity.java file.

-   True
-   False

**Correct Answer:** False

### 6. \_\_\_\_\_\_\_\_ class contains resource IDs for all the resources available in your directory.

-   R
-   xml
-   res
-   ID

**Correct Answer:** R

### 7. \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ are additional files and static content that your code uses, such as bitmaps, layout definitions, etc.

-   Receivers
-   Resources
-   Activities
-   Services

**Correct Answer:** Resources

### 8. If you want to access an image from your res folder to your Java code, what command should you use?

-   `R.res.image`
-   `res/drawable/image`
-   `R.id.image`
-   `R.drawable.image`

**Correct Answer:** `R.drawable.image`

### 9. UI elements that are drawn on-screen including buttons, lists, forms, etc.

-   Views
-   Layouts
-   Intents
-   Fragments

**Correct Answer:** Views

### 10. Manifest is a file that stores the configuration of your application.

-   True
-   False

**Correct Answer:** True

------------------------------------------------------------------------

## Module 5 --- Android Activity Lifecycle

### 1. An Android activity represents one screen of the Android application's user interface.

-   True
-   False

**Correct Answer:** True

### 2. This is the last callback method in Android's activity life cycle.

-   `onResume()`
-   `onDestroy()`
-   `onStop()`
-   `onRestart()`

**Correct Answer:** `onDestroy()`

### 3. This callback method is called when the user navigates back to the screen of your application after using another/different application.

-   `onDestroy()`
-   `onRestart()`
-   `onResume()`
-   `onPause()`

**Correct Answer:** `onRestart()`

### 4. When the user exits an application, which of the following is correct?

1.  `onStop()` will be called first before `onDestroy()`
2.  `onDestroy()` will be called first before `onStop()`
3.  The application will only call `onStop()`
4.  The application will only call `onDestroy()`

Choices: - iv only - ii and iii - i - ii only

**Correct Answer:** i --- `onStop()` will be called first before
`onDestroy()`.

### 5. When you switch from one activity to another, the first activity will no longer be visible on your screen. In this case, the callback method \_\_\_\_\_\_\_\_\_\_\_ is called.

-   `onResume()`
-   `onPause()`
-   `onDestroy()`
-   `onStop()`

**Correct Answer:** `onStop()`

### 6. Activity class takes care of creating a window for you in which you can place your UI with `setContentView(View)`.

-   True
-   False

**Correct Answer:** True

### 7. Activity is one of the most important components for any Android app. Activities are the User Interface (UI) screens which users see.

-   True
-   False

**Correct Answer:** True

### 8. You implement an activity as a subclass of the `Content Provider` class.

-   True
-   False

**Correct Answer:** False

### 9. An app is running in the foreground when a phone call arrives, displaying a small dialog-themed incoming call window over the top of the app. The user can still see the app's UI partially blurred or obscured in the background. Which lifecycle method is called on the main activity when this dialog appears?

-   `onStop()`
-   `onPause()`
-   `onSaveInstanceState()`
-   `onDestroy()`

**Correct Answer:** `onPause()`

### 10. The `onCreate()` and `onDestroy()` methods are called only once throughout the activity lifecycle.

-   True
-   False

**Correct Answer:** True

### 11. The `onResume()` callback method is called whenever the activity becomes visible to the user.

-   True
-   False

**Correct Answer:** False

### 12. An activity class loads all the UI component using the XML file during the \_\_\_\_\_\_\_\_\_\_\_\_\_ method.

-   `onResume()`
-   `onCreate()`
-   `onStop()`
-   `onStart()`

**Correct Answer:** `onCreate()`

### 13. When another activity is called within the application, the current activity will call the \_\_\_\_\_\_\_\_\_\_\_ method.

-   `onPause()`
-   `onCreate()`
-   `onStart()`
-   `onStop()`

**Correct Answer:** `onPause()`

### 14. In Android's activity life cycle, this is the first method that is called when the activity is created.

-   `onStart()`
-   `onCreate()`
-   `onResume()`
-   `onStop()`

**Correct Answer:** `onCreate()`

### 15. The `onPause()` method is required for any kind of Activity to run the application properly.

-   True
-   False

**Correct Answer:** False
