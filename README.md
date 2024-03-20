
# SoigneMOi Desktop

A desktop application to visualize the day's input and output.

Accompanies the SoigneMOi web application.

Intended for the secretaries of SoigneMOi.


---

## Distribution :

 - You can find the executable of this GitHub repository at sgm-desktop/DesktopApp/dist/sgm-desktop.exe.

---
## Code source : 

### Here are the steps to install and run the SoigneMOi Desktop application locally:

1. **Prerequisites**:
   - Install Python version 10 or higher on your local machine. You can download it from the official Python website: https://www.python.org/downloads/
   - Install Git on your local machine. You can find instructions for installing Git in the provided Git documentation: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

2. **Clone the project**:
   - Copy the GitHub repository link from the "Code" button at the top right of the page.
   - In a terminal, navigate to the local location where you want the source folder to be cloned.
   - Execute the git clone command:
     ```
     git clone https://github.com/OLCAY-GURSES/sgm_desktop
     
     ```
   - A folder named `sgm_desktop` should have been created. Navigate into it:
     ```
     cd sgm_desktop
     
     ```

3. ## Create a virtual environment**:
   - Create a virtual environment named *env* using the following command:
     ```
     python3 -m venv env
     
     ```

4. ## Activate the virtual environment**:
   - For Unix/Linux platforms:
     ```
     source env/bin/activate
     
     ```
   - For Windows (cmd.exe):
   - 
     ```
     source env/scripts/activate
     
     ```
   * For other platforms, consult the Python documentation on virtual environments: https://docs.python.org/3/library/venv.html

   Your command prompt should now be preceded by `(env)`, indicating that you are in the virtual environment.

5. ## Install the project dependencies**:
   ```
   pip install -r requirements.txt
   
   ```

6. ## Run the application**:
   ```
   py main.py
   
   ```

