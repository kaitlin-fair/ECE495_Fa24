## ECE 495 Setup Instructions

### Download Python 3.10.11 (the version matters)

- For this course, you will need a Python environment that uses **python 3.10.11** with specific software packages listed in requirements.txt in this repository. [Download Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe) - This link will download the *.exe file for Python 3.10.11.*

- Double click the downloaded file to load the installer. In the first window, *be sure to check the box that says add to PATH!* and take note of the location listed under `Install Now` (you'll need it later so write it down or take a screenshot). Then click `Install Now`.

- If something pops up about disabling path length limit, go ahead and do so.

### Install VS Code

- [Install VS Code](https://code.visualstudio.com/download) if you don't already have it.

### Create your Virtual Environment

- Make a new folder where you will store all files for this course titled `495_workspace`. I'd recommend you do this in OneDrive if you'd like cloud backup.

- [Download and save this file](_static/requirements.txt) to your `495_workspace` folder.

- Open your `495_workspace` folder in VS Code. You can do this within `Explorer` (the double page symbol on the leftmost column) by either clicking `Open Folder` or right clicking within your workspace and selecting `Add Folder to Workspace`

- Type in `>Python: Create Environment` in the searchbar at the top of VS Code and select it.

- When prompted to `Select an environment type`, select `Venv`

- If prompted to `Select a workspace to create environment`, select your `495_workspace` folder.

- When prompted to `Select a Python installation to create the virtual environment`, either choose `Python 3.10.11 64-bit` or select `Enter interpreter path...` and navigate to the Python path where you downloaded **Python 3.10.11**. This is critical: it _MUST be **Python 3.10.11**_!  

- When prompted to `Select dependencies to install`, select the `requirements.txt` file you downloaded and added to your `495_workspace` folder. Click `OK`.

- Wait for a few minutes until all the packages are installed.

- If VS Code yells at you about your Python interpreter, select the interpreter you just built (`495 Workspace`) and if prompted then choose Python 3.10.11. Otherwise you may be prompted once trying to run your test file to select an interpreter. 
  
### Test your environment

- [Go to the Setup Notebook page](495setup_LastName.ipynb) and download the Jupyter Notebook by clicking the download button at the top of the page. Save the file to your `495_workspace` folder. 

- Change the filename so that `LastName` is replaced with _your last name_.

- Open the file in VS Code and click `Run All`. 

- If VS Code tells you to select your Python interpreter, select the interpreter you just built (`495 Workspace`) and if prompted choose Python 3.10.11. If not prompted, in the search bar at the top of VS Code, type `>Python: Select Interpreter`, select the interpreter you just built (`495 Workspace`) and if prompted choose Python 3.10.11.

- It may ask you to install a Jupyter extension - if it does, do it! 

- If it runs properly, edit the title of the plot (line 57) to also display your last name. For me, the title shows "Decoded Neuron Output - Fair". Run your edited code. Your code should return 1 plot that displays the decoded neuron output with your last name in the title. Run again and save your file so that the updated plot shows in your notebook. Don't worry about understanding the code yet! We will get there later.

```{Note}
As we will use specifications grading for labs (as detailed in your syllabus), here are your specifications to earn a 1 for this lab:   
◻ Code runs error free  
◻ Filename changed to reflect last name of person submitting assignment    
◻ Plot title edited within Jupyter notebook to display your last name   
◻ Jupyter notebook is saved such that outputs appear upon opening file (and therefore on gradescope)  
```  

- Upload _only_ your `495setup_LastName.ipynb` into Gradescope under "Setup Lab" assignment by end of day T6 (23 Aug on or before 2359). You are encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)
