# CSCD496 - Spring2019
## Installing Software for Machine Learning

1. Install Virtual Box ( **If you are running ubuntu 18.04 on your system, then you can skip to step 3 below.**)

	go to [VirtualBox Wiki Downloads](https://www.virtualbox.org/wiki/Downloads) and download the version of VBox appropriate for your base operating system.  

	Installation details can be found [here](https://www.virtualbox.org/manual/ch02.html).

2. Install Ubuntu 18.04.  go to [this page](https://www.ubuntu.com/download) and download the ubuntu 18.04 desktop image.

3. Log in and update and upgrade the system.

	```
	sudo apt update
	sudo apt upgrade
	```
	
4. Install [Guest Additions](https://www.virtualbox.org/manual/ch04.html) in the ubuntu client.
	
5. Install git and prereqs for virtual environment:

	```
	sudo apt git
	sudo apt install build-essential python3-dev python3-setuptools python3-tk
	sudo apt python3-pip
	```

6. Install [python virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/#lower-level-virtualenv)

7. Create and activate a virtual environment for testing.

	```
	virtualenv -p python3 test
	source test/bin/activate
	```
	
8. Now, in the virtual environment, install pandas, statsmodel, and scikit-learn.

	```
	pip install -U numpy scipy
	pip install -U pandas statsmodels
	pip install -U scikit-learn
	pip install -U matplotlib
	pip install -U seaborn
	```
	
9. install ipython and jupyter.

	```
	pip install -U ipython jupyter
	```

10. Test using jupyter notebook.  

	First go to the test folder and create a notebook folder. then run jupyter

	```
	cd test
	mkdir projects
	cd projects
	jupyter notebook
	```
	Your browser will open up.  in the browser, you will see this:
	
	![jupyter notebook](https://github.com/JoeDumoulin/CSCD439F17/blob/master/images/2017-09-25T3.32.06PM.png "first page")
	
	Create a new notebook.  On the right of the screen select the 'New' button.
	
	![jupyter notebook](https://github.com/JoeDumoulin/CSCD439F17/blob/master/images/2017-09-25T3.46.32PM.png "select kernel")
	
	Select 'Python 3'.  A new page opens up.  you can type some python into the page and press ctrl-Enter.  the python should execute as in the example below.
	
	![jupyter notebook](https://github.com/JoeDumoulin/CSCD439F17/blob/master/images/2017-09-25T3.52.45PM.png "run python")
	
	Test if matplotlib is working.  Press '+' on the upper left of the screen.  A new code box appears.  copy and paste the following code:
	
	```
	import numpy as np
	import matplotlib.pyplot as plt

	N = 1000
	x = np.linspace(0.0, 10.0, N)
	y = np.random.rand(N)
	plt.title('Uniform Distriibution')
	plt.scatter(x,y)
	plt.show()
	```
	
	 Now run the code (ctrl-Enter) as before.  You should see the following:
	 
	 ![jupyter notebook](https://github.com/JoeDumoulin/CSCD439F17/blob/master/images/2017-09-25T3.59.48PM.png "run python")
	 
	 If you saw the plot, matplotlib is working!
	 
	 
	 
