# UPI Fraud Detection Project

## Overview
This project implements a UPI Fraud Detection system using Django. It leverages various libraries and frameworks like TensorFlow, Keras, scikit-learn, and OpenCV to detect fraudulent activities in UPI transactions. Follow the steps below to set up and run the project.

## Prerequisites
Ensure you have the following installed:

1. [Anaconda](https://www.anaconda.com/products/individual)
2. Python 3.8 or above

---

## Setup Instructions

### Step 1: Install Anaconda
Download and install Anaconda from the [official website](https://www.anaconda.com/products/individual).

### Step 2: Open Anaconda Navigator
Open Anaconda Navigator on your system.

### Step 3: Create a New Environment
1. Create a new environment with the project name:
   - Click on **Environments** > **Create**.
   - Enter the project name and select the desired Python version (e.g., Python 3.8).

### Step 4: Install Required Tools
1. In the created environment, install **cmd.exe** and **Jupyter Notebook** by navigating to the **Home** tab and installing these tools.

### Step 5: Install Dependencies
1. Open **cmd.exe** within the project environment by clicking on **Home > cmd.exe** under the environment.
2. Execute the following commands one by one:

```bash
pip install tensorflow

conda install -c conda-forge keras

conda install -c anaconda scikit-learn

conda install -c conda-forge opencv

conda install -c anaconda scikit-image

conda install -c anaconda flask

pip install pandas

pip install werkzeug==2.3.7
```

---

## Running the Project

1. **Activate the Environment:**
   Open a terminal and activate the environment:
   ```bash
   conda activate <your-environment-name>
   ```

2. **Navigate to the Project Directory:**
   Change to the directory where the project files are located:
   ```bash
   cd path/to/your/project
   ```

3. **Run the Django Server:**
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

4. **Access the Application:**
   Open your web browser and go to:
   ```
   http://127.0.0.1:8000/
   ```

5. **Perform Tests:**
   Use the provided interface to test UPI transactions and analyze the fraud detection results.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---




