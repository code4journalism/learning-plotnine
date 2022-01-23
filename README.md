# learn-plotnine
Lesson plan for exploratory data visualization!

## Setup

1. Make sure you have the following packages:
		
	```shell
	pip3 install jupyter plotnine pandas
	```

2. Make sure you're in the right folder on your terminal (I like to store things in my `~/Development` folder, but you can keep them elsewhere if you prefer).
	
	```shell
	# enter the folder where you plan to clone this repo
	cd ~/Development
	
	# make sure you got there (read the output!)
	pwd
	```

3. Next, clone this repository by clicking the green button in the upper right corner, selecting `SSH` and copying the string that looks like `git@github.com:code4policy/<REPO-NAME>.git` (`<REPO-NAME>` will be the name of your repository). Then, in the terminal run the following:
	
	```shell
	git clone git@github.com:code4policy/<REPO-NAME>.git
	```

	Note that by default, git will clone the repository into a folder with name `<REPO-NAME>`. After the repo is cloned, open that directory (use `cd` to get into the folder you just cloned).

4. Run the jupyter notebook and open up `exploratory-data-analysis.ipynb`

	```shell
	jupyter notebook
	```

	Make sure you're using a python3 kernel in Jupyter!