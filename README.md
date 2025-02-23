# datafun-06-eda.
Start a New Project

# 1. Project Setup

Create repo named datafun-04-eda in browser with a default README.md.
Clone repo to local
git clone (paste repo URL)
Create .gitignore file in root project folder
Copy/pasted template from Module 4 example
Add requirements.txt in root project folder
Copy/pasted template from Module 4 example and added pyarrow and jupyterlab
# 2. Git add-commit-push

Push changes from local to GitHub with clear commit message.

git add .
git commit -m "Add a message with a clear and descriptive note about what you added or changed."
git push
# Create Virtual Environment

# 1. Create .venv
py -m venv .venv
# 2. Activate Virtual Environment

Always make sure to be in the virtual environment when installing packages and running scripts.

.venv\Scripts\activate
# 3. Set VS Code Interpreter

Open Command Palette: Ctrl+Shift+P
Search "Python: Select Interpreter"
Chose local .venv option
External Dependencies
Install necessary dependecies for the project using requirements.txt file.
Known dependencies for this project at the start:

jupyterlab
pandas
pyarrow
matplotlib
seaborn
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt

# Create Jupyter Notebook

# 1. Open VS Code and make sure you've installed both Python and Jupyter extensions.

Open the Command Palette by pressing Ctrl+Shift+P or Cmd+Shift+P (on macOS).
Type and select "Jupyter: Create New Blank Notebook".

# 2. Create a New File:

Open the Command Palette by pressing Ctrl+Shift+P or Cmd+Shift+P (on macOS).
Type and select "Jupyter: Create New Blank Notebook".
You can select the Python interpreter by clicking on the "Select Kernel" button in the top-right corner of the notebook interface.

# Step 3: Start Writing Code in the Jupyter Notebook

Now you can start writing Python code in the notebook cells and execute them.
Click on the "Run" button next to each cell to execute the code. Alternatively, you can use Shift+Enter to run the code in the current cell.

# Step 4: Save the Notebook

To save your notebook, click File > Save or press Ctrl+S (Cmd+S on macOS).

# Step 5: Install Jupyter (if needed)

In case you don't have Jupyter installed, you can install it via pip:

bash
Copy
pip install jupyter

When using a virtual environment, activate the environment and then install Jupyter.
