# EX-1: INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO

**Name:** BARATH V

**Register Number:** 212225240023

## Software Requirements

- Android Studio
- Android SDK
- Android Virtual Device (AVD)
- Java
- XML

---

## Step 1 – System Requirements

The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement the calculator's functionality, and XML is used to design the user interface.

### Required Software

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Emulator

---

## Step 2 – Setup Android Studio

Android Studio is the official Integrated Development Environment (IDE) used for Android application development.

### Installation Procedure

1. Download Android Studio from the official website.
2. Run the installer and follow the installation instructions.
3. Install the required Android SDK components.
4. Configure the Android SDK location.
5. Set up the Android Virtual Device if required.
6. Launch Android Studio.
7. Create a new Android project using the Empty Views Activity template.
8. Select Java as the programming language.

---

## Creating the Calculator Application

1. Open the project in Android Studio.
2. Design the calculator interface using the `activity_main.xml` file.
3. Add an EditText or TextView to display the input and calculation results.
4. Add buttons for digits from 0 to 9.
5. Add arithmetic operation buttons for addition (+), subtraction (−), multiplication (×), and division (÷).
6. Add a Clear button to reset the input and a button to calculate the result (=).
7. Open the `MainActivity.java` file.
8. Initialize the required TextViews, EditTexts, and Buttons using `findViewById()`.
9. Implement button click events using `setOnClickListener()`.
10. Write the logic to perform arithmetic operations based on the selected operator.
11. Display the calculated result on the calculator screen.
12. Handle invalid inputs and division by zero appropriately.

---

## Step 3 – Create Android Virtual Device (AVD)

An Android Virtual Device is used to test and run the application without requiring a physical Android phone.

### Procedure

1. Open Device Manager in Android Studio.
2. Click **Create Virtual Device**.
3. Select a suitable device configuration.
4. Select and download an Android system image if required.
5. Finish the configuration and start the emulator.
6. Select the emulator from the device dropdown menu.

---

## Step 4 – Run the Application

1. Open the Calculator project in Android Studio.
2. Select the configured Android Emulator.
3. Click the **Run ▶** button in Android Studio.
4. Wait for the application to build and launch.
5. Verify that the Calculator screen appears.
6. Enter numerical values using the calculator buttons.
7. Select an arithmetic operation and press the equals (=) button.
8. Verify that the correct result is displayed.
9. Test the Clear button and other arithmetic operations.

---

## Output

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c58c8496-ffe5-4fb1-b2b0-6ca2579fc77d" />


## Result

Thus, a Calculator Android application was designed and implemented using Android Studio, Java, and XML. The application was successfully run on an Android Virtual Device, and its arithmetic operations were tested.
