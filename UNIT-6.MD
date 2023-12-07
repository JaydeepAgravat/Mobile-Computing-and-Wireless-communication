# UNIT-6

## 1. Define and explain various Android Layouts

Android layouts are used to define the structure and appearance of the user interface (UI) in an Android application. They are XML files that specify how the elements (widgets) should be arranged on the screen. Here are some common Android layouts:

1. **Linear Layout:**
   - Arranges elements in a single line either horizontally or vertically.
   - Attributes: `android:orientation="horizontal"` or `android:orientation="vertical"`.

2. **Relative Layout:**
   - Places elements relative to each other or the parent.
   - Uses attributes like `android:layout_below`, `android:layout_above`, etc.

3. **Constraint Layout:**
   - Allows positioning of elements using constraints to create complex UIs.
   - It's suitable for responsive and dynamic UIs.

4. **Frame Layout:**
   - Places elements on top of each other. Only the last added element is visible.
   - Often used for simple tasks, like displaying a single image.

5. **Table Layout:**
   - Organizes elements in rows and columns, similar to an HTML table.
   - Uses `TableRow` for defining rows and `TableLayout` for the overall structure.

6. **Grid Layout:**
   - Organizes elements in a grid of rows and columns.
   - Useful for creating complex layouts with aligned elements.

7. **Coordinator Layout:**
   - Extends FrameLayout and is designed for coordinating animations between child views.
   - Useful for creating interactive and dynamic UIs.

## 2. Draw and explain Android Architecture

The Android architecture consists of several layers:

1. **Linux Kernel:**
   - Provides core system services like security, memory management, process management, and more.

2. **Hardware Abstraction Layer (HAL):**
   - Interfaces between the hardware and the higher-level Android software stack.

3. **Native Libraries:**
   - Libraries written in C/C++ that provide essential features, including graphics, media, and SQLite database support.

4. **Android Runtime (ART):**
   - Executes and compiles application code using ahead-of-time (AOT) compilation.

5. **Java API Framework:**
   - Core Java libraries providing a wide range of functionalities like UI, data structure, networking, etc.

6. **System Apps:**
   - Pre-installed apps that come with the Android system, such as the Phone app, Contacts app, etc.

7. **Application Framework:**
   - Provides the classes and services used by developers to create Android applications.

8. **Application Layer:**
   - The layer where user-installed applications reside and interact with the Android system.

![Android Architecture](https://i.imgur.com/U5UvA7s.png)

## 3. Define Android Activity and Write Android Activity Life cycle

**Android Activity:**

- An activity represents a single screen with a user interface in an Android application.

**Android Activity Lifecycle:**

1. **onCreate():**
   - Called when the activity is first created.
   - Initialization of essential components.

2. **onStart():**
   - Called when the activity becomes visible to the user.
   - Preparing the UI to be visible.

3. **onResume():**
   - Called when the activity starts interacting with the user.
   - Acquiring resources, such as the camera.

4. **onPause():**
   - Called when the activity is partially obscured but still visible.
   - Saving user changes and persisting data.

5. **onStop():**
   - Called when the activity is no longer visible to the user.
   - Releasing resources that are not needed while the activity is not visible.

6. **onDestroy():**
   - Called before the activity is destroyed.
   - Cleaning up resources and performing final operations.

7. **onRestart():**
   - Called when a stopped activity is about to be started again.
   - Preparing the activity for a new user interaction.

The Android activity lifecycle allows developers to manage the state and behavior of their applications based on the user's interactions and the current state of the system.
