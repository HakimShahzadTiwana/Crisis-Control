
# CrisisControl

CrisisControl is an Android application designed to facilitate donations and provide vital crisis-related information. Users can donate money via JazzCash to NGOs seeking funding for various crises. The app also includes a newsfeed for ongoing crises in Pakistan and helps users find the nearest donation stands for food, clothes, and other items.

This README provides instructions on how to set up and run the application, as well as an overview of the design patterns used in the project.

---

## Section 1: Setup Instructions

### Prerequisites
- Ensure the latest version of **Android Studio** is installed on your device.

### Steps to Run the Application
1. **Copy the Code Folder**  
   Copy the `Code` folder to your device.

2. **Open Android Studio**  
   Launch Android Studio on your system.

3. **Open the Project**  
   - Select the **"Open"** option.
   - Navigate to the location where you pasted the `Code` folder.  
     Open the project at `Code -> CrisisControl`.

4. **Set Up SDK Path**  
   - If the folder is not in the directory where Android Studio's SDK is installed, Android Studio will prompt you to update the Gradle path. Click **OK**.  
   - If not prompted, manually update the SDK path by editing the `local.properties` file:
     ```properties
     sdk.dir=<your_sdk_path>
     ```

5. **Run the Application**  
   - Run the app on an **emulator** or a **physical device** using Android Studio.  

   **Note**: To use the maps feature on an emulator, configure your current location in the emulator settings.

---

## Section 2: Design Patterns Used (Explicitly)

### Singleton Design Pattern
The Singleton design pattern has been applied in the following classes:
1. **`CurrentAccount.java`**  
   Path: `Code/CrisisControl/app/src/main/java/com/example/testing/classes/CurrentAccount.java`

2. **`CCDatabase.java`**  
   Path: `Code/CrisisControl/app/src/main/java/com/example/testing/classes/CCDatabase.java`


