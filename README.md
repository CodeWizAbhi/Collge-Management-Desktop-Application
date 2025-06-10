# Collge-Management-Desktop-Application
# Dev - Mr. Abhishek Lohot
# Email ID - lohotabhishek16@gmail.com
To run a NetBeans project from a ZIP file, follow these simple steps:

✅ Step-by-Step: Open and Run a NetBeans ZIP Project

🔹 Step 1: Extract the ZIP</br>
    Right-click the .zip file.</br>
    Select "Extract All..." or use any extraction tool (WinRAR, 7-Zip).</br>
    Choose a location (e.g., Documents/NetBeansProjects) and extract.</br>

🔹 Step 2: Open NetBeans</br>
    Launch NetBeans IDE.</br>

🔹 Step 3: Open the Project</br>
    Go to File > Open Project.</br>
    Browse to the folder where you extracted the ZIP.</br>
    You should see the project listed (with a folder icon).</br>
    Click on it and hit "Open Project".</br>
    🟡 If it says "Broken Reference", don’t worry—we’ll fix that in the next step.</br>

🔹 Step 4: Fix Broken References (if any)</br>
    If the project uses JavaFX or other libraries:</br>
    Right-click the project > Properties.</br>
    Go to Libraries > Compile tab.</br>
    Click "Add JAR/Folder" and locate the required .jar files (e.g., JavaFX SDK).</br>
    If it's a JavaFX project, also:</br>
    Go to Run > VM Options.</br>
    Add:</br>
      cpp</br>
      Copy</br>
      Edit</br>
      
    --module-path "C:\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml

🔹 Step 5: Clean and Build</br>
      Right-click on the project > Clean and Build.</br>
      This compiles your code and checks for errors.</br>

🔹 Step 6: Run the Project</br>
      Right-click the project again > Run.</br>
      Your Java app will start.</br>
<h1>IG-@abhishek_lohot</h1></br>
