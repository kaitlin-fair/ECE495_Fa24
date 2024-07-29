## ECE 495 Setup Assignment Instructions

### Download Required Software

- For this course, you will need a Python environment that uses **python 3.10.11** with specific software packages listed in requirements.txt in this repository. [Download Python 3.10.11](https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe) - This link will download the *.exe file for Python 3.10.11. Double click the downloaded file to start the installer. *Be sure to check the box that says add to PATH!*

- [Install VS Code](https://code.visualstudio.com/download) if you don't already have it.

### Create your Virtual Environment

- Make a new folder where you will store all files for this course titled `495_workspace`. I'd recommend you do this in OneDrive if you'd like cloud backup.

- [Download and save this file](_static/requirements.txt) to your `495_workspace` folder.

- Create a virtual environment using Python 3.10.11. The process to do so is to create a new environment using Python 3.10.11, activate the new environment, then download the packages using the requirements.txt file. 
  
### Test your environment

- [Go to the Setup Notebook page](nengo_495setup.ipynb) and download the Jupyter Notebook by clicking the download button at the top of the page. Save the file to your `495_workspace` folder. 
- Open the file in VS Code and click `Run All`. 
- It may ask you to install a Jupyter extension - if it does, do it! 
- If it runs properly, edit the title of the plot (line 57) to also display your last name. For me, the title shows "Decoded Neuron Output - Fair". Run your edited code. Your code should return 1 plot that displays the decoded neuron output with your last name in the title. Run again and save your file so that the updated plot shows in your notebook. Don't worry about understanding the code yet! We will get there later.
- Upload _only_ your `nengo_495setup.ipynb` from GitHub into Gradescope under "Setup Lab" assignment by T4, 1159. You are encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)
