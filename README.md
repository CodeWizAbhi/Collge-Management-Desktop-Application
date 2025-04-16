# Collge-Management-Desktop-Application
# Dev - Mr. Abhishek Lohot
# Email ID - lohotabhishek16@gmail.com
To run a NetBeans project from a ZIP file, follow these simple steps:

✅ Step-by-Step: Open and Run a NetBeans ZIP Project
🔹 Step 1: Extract the ZIP
Right-click the .zip file.

Select "Extract All..." or use any extraction tool (WinRAR, 7-Zip).

Choose a location (e.g., Documents/NetBeansProjects) and extract.

🔹 Step 2: Open NetBeans
Launch NetBeans IDE.

🔹 Step 3: Open the Project
Go to File > Open Project.

Browse to the folder where you extracted the ZIP.

You should see the project listed (with a folder icon).

Click on it and hit "Open Project".

🟡 If it says "Broken Reference", don’t worry—we’ll fix that in the next step.

🔹 Step 4: Fix Broken References (if any)
If the project uses JavaFX or other libraries:

Right-click the project > Properties.

Go to Libraries > Compile tab.

Click "Add JAR/Folder" and locate the required .jar files (e.g., JavaFX SDK).

If it's a JavaFX project, also:

Go to Run > VM Options.

Add:

cpp
Copy
Edit
--module-path "C:\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml
🔹 Step 5: Clean and Build
Right-click on the project > Clean and Build.

This compiles your code and checks for errors.

🔹 Step 6: Run the Project
Right-click the project again > Run.

Your Java app will start.
