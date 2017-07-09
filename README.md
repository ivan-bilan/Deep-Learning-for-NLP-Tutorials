# Installation Guide
## Use Python 3.5 or higher

To save time on Thursday consider preparing the environment before the class starts. You can remotely connect to the university PC with your "Remote Desktop" manager of choice and connect to ```remote.cip.ifi.lmu.de``` and then log-in as usual.

### Step 1, clone the GitHub project
Go to https://github.com/ivan-bilan/Tensorflow-for-NLP-Tutorials
Press: _"Clone and Download"_

Navigate to the folder you want to install the project in and do:

```
git clone https://github.com/ivan-bilan/Tensorflow-for-NLP-Tutorials.git
```

### Step 2, Jupyter Notebooks
Install Jupyter Notebook

    pip3 install jupyter

### Starting the Notebook
##### In PyCharm
If you use PyCharm, simply use the Start button on the main project file _tensorflow_basics.ipynb_ and copy the generated URL with the security token, e.g.: 
```http://127.0.0.1:8888/?token=11cff7e3126674b2cdd8093a1xxx954a67```. 
Open the URL in your browser. That's it!

##### In terminal
Run from terminal:
    
    jupyter notebook
    
it will navigate to your home folder, go to the project folder using the Jupyter file browser.

##### For both solutions, use Chrome or Chromium. Firefox won't work with certain examples.

### Step 3, Tensorflow and related packages
Now let's install _tensorflow_ and _tflearn_.

##### On your own laptop
If you have your own laptop with you with _sudo_ access, just run there commands in your terminal:

    pip3 install tensorflow 
    pip3 install tflearn
    pip3 install numpy
    pip3 install pandas==0.19.2

##### University PC

###### Option 1

Install pip packages only for your local user:
 
    pip3 install --user tensorflow 
    pip3 install --user tflearn
    pip3 install --user numpy
    pip3 install --user pandas==0.19.2

###### Option 2

If you have _PyCharm_ installed, just do the following: 

_File > Project xx > Project Interpreter > Select the "+" on the right top side > search for _ternsorflow_ > press "Install Package"_

Should work without any errors. Do the same for _tflearn, numpy and pandas_.


### Alternative: Running Jupyter Notebook in the cloud

If you want to skip local installation, use cocalc.com
sign-up with GitHub/Google
1) create new project
2) choose JupyterNotebook as type
3) go to "Kernel" menu, and choose Python 3 (Anaconda)

Now you have an IpythonPython Notebook with _tensorflow_ installed and running in the cloud.










    

