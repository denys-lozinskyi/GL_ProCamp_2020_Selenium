**Homeworks for GL QA Automation ProCamp'2020,
Selenium section**

**For all homeworks:**
1. Create virtual environment;
2. Activate the virtual environment;
3. Install all the libraries from the requirements file in the root folder:

    _$ pip install -r requirements_

**For homework_1:**
1. cd into the homework_1 folder;
Please note, the homework_1 code gives you possibility to run tests with either Chrome or Opera browser. Chrome is set by default;
2. run pytest with the key -v (more readable output):

    _(venv) user@user: GL_ProCamp_2020_Selenium/homework_1$ pytest -v_

**For homework_2:**
1. install Selenium server, download webdrivers for your browsers and place them into the folder with your selenium server file;
Please note, the homework_2 code gives you possibility to run tests with either Chrome or Opera browser. Chrome is set by default;
2. run the selenium server. In the pages/base_page.py replace the url in the command_executor parameter with the one
your selenium server in being run on; 
3. cd into the homework_2 folder;
4. run pytest with the key -v (more readable output):

    _(venv) user@user: GL_ProCamp_2020_Selenium/homework_2$ pytest -v_

**For homework_3:**
1. cd into the homework_3 folder;
2. run pytest with keys -v and -s (-s enables stdout capturing for the listener's output, -v - makes the output more readable):
All the test specified in the HW3 tasks will run separately and one by one within the scope of the test suite 

    _(venv) user@user: GL_ProCamp_2020_Selenium/homework_3$ pytest -vs_
