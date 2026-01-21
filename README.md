 # AI-Powered IDS for CAN Networks
**Execution Guide Using Google Colab & Google Drive**

---

## 1. Overview  
This repository contains the implementation of the **Car Security Project** using a Jupyter Notebook (`.ipynb`). The project is intended to be executed on **Google Colab**, with all datasets and model files accessed through **Google Drive** for smooth cloud-based execution.

---

## 2. Prerequisites  

Before starting, ensure you have the following:

- A Google Account  
- Access to Google Drive  
- Access to Google Colab  
- A stable internet connection  

---

## 3. Complete Project Setup Instructions  

### Step 1: Upload the Notebook to Google Drive  

1. Download the `.ipynb` file from this GitHub repository.
2. Open **Google Drive**.
3. Upload the `.ipynb` notebook file to your Drive.

---

### Step 2: Download Dataset from Public Drive Link  

1. Open the **public Google Drive dataset link** provided in this repository.
2. https://drive.google.com/drive/folders/1DtP610qJ0uoy7l6zrNHytf6EJfCPGmV9?usp=sharing
3. Download all dataset files to your local system.
4. Open **Google Drive** again.
5. Create a folder named exactly:


6. Upload all downloaded **dataset files** into this `car-sec-project` folder.

---

### Step 3: Organize All Project Files in One Folder  

Inside the `car-sec-project` folder in your Google Drive, place:

- Dataset files  
- Model files (if any)  
- The `.ipynb` notebook inside a dedicated `notebooks/` folder  

Your final folder structure must look exactly like this:

```md
car-sec-project/
│
├── datasets/
├── models/
├── notebooks/
│   └── car_security_project.ipynb
```



---

## 4. Opening the Project in Google Colab  

1. Open Google Colab:  
   https://colab.research.google.com  

2. Click on:  
   **File → Open Notebook → Google Drive**

3. Select the notebook from:


4. Once the notebook loads, all code cells will be visible.

---

## 5. Running the Project  

1. Run each code cell **one by one from top to bottom**.
2. The notebook will automatically access:
   - The dataset from the `datasets/` folder  
   - The model files from the `models/` folder  

3. Do not skip any cells to avoid execution errors.

---

## 6. Important Guidelines  

- Make sure you are logged into the **same Google account** where your project files are stored.  
- Do **not rename** the `car-sec-project` folder.  
- Do **not change** the internal file paths unless absolutely required.  
- Always execute the notebook cells **sequentially**.

---

## 7. Expected Output  

After successful execution, the project will:

- Load the dataset from Google Drive  
- Perform data preprocessing  
- Train and/or evaluate the model  
- Display the final results and outputs  

---

## 8. Support  

If you face any issues during execution:

- Recheck the Google Drive folder structure  
- Ensure correct dataset placement  
- Verify all file paths inside the notebook  
- Reconnect Google Drive in Colab if required  

---

✅ This setup ensures smooth and error-free execution of the project on Google Colab.
