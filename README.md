# Calculator App SwiftUI Document

SwiftUI is a modern and declarative framework for building user interfaces across Apple platforms, including iOS, macOS, watchOS, and tvOS. In this documentation, we will guide you through the process of building a calculator app in SwiftUI.


Step 1: Setting Up a New Project
1. Open Xcode and select “Create a new Xcode project”.
2. Select “iOS” as the platform and choose “App” as the template for your project.
3. Enter the name of your project and select SwiftUI as the user interface.
4. Click “Next” and select the folder where you want to save your project.
5. Click “Create” to create the project.


Step 2: Designing the User Interface
1. Open the ContentView.swift file and remove the default code.
2. Define a VStack to hold the calculator buttons.
3. Add an HStack to hold the display label and the clear button.
4. Define a Text view to display the result.
5. Add a ForEach loop to create the buttons for the calculator.
6. Define a Button for each calculator button and add the appropriate action.


Step 3: Adding the Calculator Logic
1. Create a struct called “Calculator” to hold the calculator logic.
2. Define a variable called “result” to hold the current result.
3. Define a variable called “operation” to hold the current operation.
4. Define a function called “calculate” to perform the calculation.
5. Add a switch statement to handle each calculator button.


Step 4: Wiring up the User Interface and Logic
1. Create an instance of the Calculator struct in the ContentView struct.
2. Add an @State variable called “display” to hold the text to be displayed on the screen.
3. Add an @State variable called “clear” to determine whether the “C” button has been pressed.
4. Bind the Text view to the display variable.
5. Bind the “C” button action to the clear variable.
6. Bind the calculator buttons to the appropriate action in the Calculator struct.
7. Call the calculate function in each button action and update the display variable.


Step 5: Testing the App
1. Build and run the app in the simulator.
2. Test each calculator button to make sure it performs the correct operation.
3. Test the clear button to make sure it resets the display to zero.
4. Test the app on different devices and orientations to ensure it works as expected.


Conclusion:
In this documentation, we have walked you through the process of building a calculator app in SwiftUI. By following these steps, you should have a fully functional calculator app that you can use as a starting point for more complex apps. Keep practicing and exploring the capabilities of SwiftUI to build more advanced and powerful apps.
