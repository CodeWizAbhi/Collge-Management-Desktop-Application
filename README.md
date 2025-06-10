# 🎓 College Management Desktop Application

# Developer:** Mr. Abhishek Lohot  
# Email:** lohotabhishek16@gmail.com

---

## 📦 How to Open and Run the Project in NetBeans

Follow these simple steps to set up and run the project from a ZIP file using NetBeans IDE.

---

### ✅ Step-by-Step Guide

### 🔹 Step 1: Extract the ZIP File
- Right-click the `.zip` file.
- Choose **"Extract All..."** or use an extraction tool like **WinRAR** or **7-Zip**.
- Extract the project to a folder (e.g., `Documents/NetBeansProjects`).

### 🔹 Step 2: Launch NetBeans
- Open **NetBeans IDE**.

### 🔹 Step 3: Open the Project
- Go to **File > Open Project**.
- Navigate to the extracted project folder.
- Select the project (with a folder icon) and click **Open Project**.

> 🟡 If you see "Broken Reference" warnings, continue to Step 4.

### 🔹 Step 4: Fix Broken References (If Any)
#### If the project uses JavaFX or other external libraries:

- Right-click the project > **Properties**
- Go to **Libraries > Compile**
- Click **Add JAR/Folder** and locate required JAR files (e.g., JavaFX SDK)

#### For JavaFX projects:
- Go to **Run > VM Options**
- Add the following line (replace the path as per your system):
  
      --module-path "C:\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml
### 🔹 Step 5: Clean and Build the Project
-Right-click the project > Clean and Build
-This compiles the code and checks for errors.

### 🔹 Step 6: Run the Project
-Right-click the project > Run
-The application should now start successfully.
