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

- *Optional:* Run Black to check your code for minor errors and improper formatting using the following command in the terminal within VS code: `black --check .` If the output _does not_ say "All done! ✨ 🍰 ✨ 1 file would be left unchanged.", it will instead give a message along the lines of a file should be reformatted. This simply means that your code may not be as neat as possible. When your code is neat, it's far easier to grade and therefore easier to give you the credit you deserve! To resolve the issue you'll need to edit your code; however, this is not a requirement. If you choose to make edits, you can take a look at how Black would reformat your code using `black --diff .` Edit the code accordingly to resolve the issue and run again. Repeat until the output is "All done! ✨ 🍰 ✨ 1 file would be left unchanged.". You could also simply run `black .` to automatically make the changes, but I strongly recommend you understand what changes are made prior to submitting your file. Note that the autograder in Gradescope will run black and display results much like those described above. You will not lose any credit for not getting the "All done!" statement, BUT if your code is illegible or tough to understand, it'll be difficult to grade and please recall that you either earn a score of entirely right (1) or some version of wrong (0). Make your submission count! For troubleshooting and more ways to use Black you can visit [this site](https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html). 

- Upload _only_ your `495setup_LastName.ipynb` into Gradescope under "Setup Lab" assignment by end of day T6 (23 Aug on or before 2359). You are encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)
