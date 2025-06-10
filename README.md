🎓 College Management Desktop Application
Developer: Mr. Abhishek Lohot
Email: lohotabhishek16@gmail.com

📦 How to Open and Run the Project in NetBeans
Follow these simple steps to set up and run the project from a ZIP file using NetBeans IDE.

✅ Step-by-Step Guide
🔹 Step 1: Extract the ZIP File
Right-click the .zip file.

Choose "Extract All..." or use any extraction tool like WinRAR or 7-Zip.

Extract it to a preferred location (e.g., Documents/NetBeansProjects).

🔹 Step 2: Launch NetBeans
Open NetBeans IDE on your system.

🔹 Step 3: Open the Project
Go to File > Open Project.

Browse to the folder where you extracted the ZIP file.

You should see the project folder (NetBeans will show it with a folder icon).

Select it and click "Open Project".

🟡 Note: If you see a "Broken Reference" warning, proceed to the next step.

🔹 Step 4: Fix Broken References (If Any)
If your project uses external libraries like JavaFX, follow these steps:

Right-click the project > Properties

Navigate to Libraries > Compile

Click Add JAR/Folder and browse to add required JAR files (e.g., from the JavaFX SDK)

For JavaFX projects:

Go to Run > VM Options

Add the following line (update the path to your JavaFX SDK location):

sh
Copy
Edit
--module-path "C:\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml
🔹 Step 5: Clean and Build the Project
Right-click the project > Clean and Build

This compiles the project and checks for any errors.

🔹 Step 6: Run the Project
Right-click the project again > Run

Your Java desktop application should now launch successfully!

📲 Social
Instagram: @abhishek_lohot
