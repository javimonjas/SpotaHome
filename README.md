**Installation Instructions**

Its recommended in order to avoid compatibility issues with former installed libraries, that the person who is going to review this code create a virtual environment and install the exact version of the libraries that come in the requirements.txt file.

To create the virtual environment we use the following instruction on the command line:

```python -m venv spotahome``` (virtual environment name)

Then we activate said virtual environment with the following instruction:

* If you are in a Windows environment:  
    `.\spotahome\Scripts\activate`  

* If you are in UNIX/Linux enviroment:  
    `source spotahome/bin/activate`

After that you should see (spotahome) before your command prompt.

At this time you should install the proper libraries via pip install with the following instruction:

`pip install -r requierements.txt`

after that you should run the jupyter notebook using this intruction:

`jupyter notebook --port=XXXX`   
Change the default port if you have an old instance of jupyter notebook running.

NOw you will be able to run my code and to see the results of this task.




