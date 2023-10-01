# Sppu Parser (Hacktoberfest 23)

## **Project Overview**

The project involves working with PDF files released by SPPU (Savitribai Phule Pune University) for each college per semester. These PDF files contain a variety of information related to students and their academic performance, including:

`student_name`, `student_prn`, `student_mother_name`, `subject_code`, `ise_score`,`ese_score`, `total_score`,`tw_score`,`pr_score`,`or_score`, `crd_score`, `grade`, `grade_point`, `credit_point`, `sgpa` , `total_credits` 

The project has two main objectives:

### **1. PDF Parsing**

Develop a Python program that can automatically parse the PDF files provided by SPPU to extract all the relevant data mentioned above.

### **2. Data Analysis and Visualization**

Create a data pipeline that processes the parsed data to derive insights and generate graphs or visualizations to facilitate a better understanding of the academic performance of students.

## **Project Setup**

To set up a virtual environment and run the `.ipynb` file from the repository `https://github.com/notcostheta/sppu-parser`, follow these steps:

1. **Clone the Repository:**

   Open your terminal or command prompt and navigate to the directory where you want to clone the repository. Then, run the following command to clone the repository:

   ```bash
   git clone https://github.com/notcostheta/sppu-parser
   ```

   This will create a local copy of the repository in a directory named `sppu-parser`.

2. **Navigate to the Repository Directory:**

   Use the `cd` command to move into the `sppu-parser` directory:

   ```bash
   cd sppu-parser
   ```

3. **Create a Virtual Environment:**

   Now that you're inside the repository directory, create a virtual environment named `.venv` using Python's `venv` module:

   ```bash
   python -m venv .venv
   ```

4. **Activate the Virtual Environment:**

   Depending on your operating system, activate the virtual environment:

   - **Windows:**

     ```bash
     .venv\Scripts\activate
     ```

   - **macOS and Linux:**

     ```bash
     source .venv/bin/activate
     ```

5. **Install Dependencies:**

   With the virtual environment active, install the required dependencies by running:

   ```bash
   pip install -r requirements.txt
   ```

   This command will install the necessary packages specified in the `requirements.txt` file.

6. **Run the Jupyter Notebook:**

   After successfully setting up the virtual environment and installing dependencies, you can run the Jupyter Notebook file (`.ipynb`). Assuming the notebook is named `your_notebook.ipynb`, run the following command:

   ```bash
   jupyter notebook your_notebook.ipynb
   ```

   This will open the Jupyter Notebook in your web browser, allowing you to interact with and execute the code within the notebook.

7. **Deactivate the Virtual Environment:**

   When you're finished working with the notebook and want to exit the virtual environment, run the `deactivate` command:

   ```bash
   deactivate
   ```

   This will return you to the global Python environment.

By following these steps, you'll have set up a virtual environment, installed the necessary dependencies, and run the Jupyter Notebook from the `sppu-parser` repository for your project.