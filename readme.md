# Hotel Content Based Recommender

## Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8.


2. Install [Git](https://git-scm.com/downloads).


3. Install [PyCharm](https://www.jetbrains.com/pycharm/) (community version).


4. Go to the chosen folder on your machine where you want to have a local copy of the repository. Right-click in the folder and from the context menu choose "Git Bash Here". Run the following command to clone the forked repository on your GitHub account to your local machine:

	<pre>git clone <i>https://github.com/jbiesek/ContentBasedRecommender.git</i></pre>

	Alternatively, open Git Bash (installed with Git), change the path to the folder where you want to have a local copy of the repository, execute the above command.


5. Prepare your conda environment (instructions given for Windows, but it should be similar on other systems):

	1. Open Anaconda Prompt as administrator.

	2. Make sure you're in the repository main folder. Run the following command:
			
			conda env create --name recommender -f environment.yml
		
		You may need to install a C++ compiler to install certain packages.


6. In Git Bash open the repository folder and activate just created environment with the following command:

		conda activate rs-class-env

7. You may need to type:

		pip install tqdm
		
		pip install future

8. In Git Bash type:

		jupyter notebook

	A new tab with Jupyter Notebook should open in your browser.


9. In Jupyter Notebook open project_1_recommender_and_evaluation.ipynb.


10. Click on the first cell and hit shift+enter. The first cell should get executed properly. Do the same for all other cells (you can continuously hit shift+enter until you execute all cells).

