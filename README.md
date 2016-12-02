Pythoncoaching
===================

#### <i class="icon-upload"></i> Clone with Pycharm


- IDE Pycharm > VCS > Checkout form version control > Github:
	- Repository URL:  https://github.com/KhaosResearch/Pythoncoaching.git
- Create virtualenv environment into project:
	- File > settings > Search 'Project Interpreter'. Click to 'create virtualenv'.
	- In the new window opened, type name 'env'. Place it within the project directory. Choose the python3 interpreter. Click 'Ok'.
	- Once the virtual environment is created, update the three dependencies that you have installed virtualenv: pip, setuptools y wheel (select it and click to blue up arrow).
	- Click to 'Apply'.
- Install dependencies
	- Open the Pycharm terminal by pressing ALT + F12.
	- Access the virtual environment of the project:
	   source venv//bin/activate
	- Install the dependencies defined in requirements.txt:
	   pip freeze > requirements.txt