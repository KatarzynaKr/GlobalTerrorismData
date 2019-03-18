# Global Terrorism Project
Biomedical engineering - miniproject - data exploration


## Project Instructions

0. (Optional step) Fork the repository to your githab account. It allows you to upload the changes to your own github

1. Clean all the previous copies of this repo (it could be downloaded by other students).

    ```
    cd
    ls -all
    rm -rf bme-*
    ```

2. Clone the repository to your local PC

    Go to your home directory, and clone the repository. In case you made a copy (fork) provide your own URL
    ```
    cd
    git clone https://github.com/tstokrk/bme-data-exp.git
    cd bme-data-exp
    ```

3. (Optional step) Create a new conda environment.

    If you're using mini conda this step help you tune the the necessary Python packages.

    All necessary packages are listed in requirements.yml file, that defines dataexp env.

    Before you create the new dataexp env using conda, check if there is no different
    env with the same name on your PC. Remove all env that can create a conflict with the new one

    ```
    conda env list
    conda env remove --name dataexp
    ```

    Create the new env using the package list from the provided file

    ```
    conda env create -f requirements.yml
    source activate dataexp
    ```


4. Open the Jupyter Notebook and follow the instructions
	
    ```
    jupyter notebook dataexp.ipynb
    ```
  
5. (Optional step) Commit and push all the changes to your own github repo 

    ```
    git commit -m "My update.."
    git push origin master



Instructions:

    Download data set, Global Terrorism Database, from https://www.kaggle.com/START-UMD/gtd
    Take a quick look at the data set. Check what's inside, how the data is structured, and where the data is corrupted (missing values, bad structure, etc).
    Think and create 5 questions to the data. Try to ask yourself what's really interesting in the data set. What's not so obvious. E.g. some trends, patterns, correlations.
    Create a jupyter notebook and use python, numpy, pandas, matplotlib (at least) to provide all the answers to your questions.
    Create a new github repository, and put your jupyter notebook there.
    Create readme.md file as well in your github root directory with all necessary instructions (what is in the repo, what libs are necessary to run the code, where to find data set and where to save it - this is necessary because the dataset is too big for github repo).
    Provide the necessary documentation and introduction in your notebook using markdown language, at least: data source description, data structure, importing process, data processing process.
    Put some data visualization in your notebook. Sometimes it's much easier to present the answer using a chart rather than numbers
    Check if your notebook run smoothly - use 'Reset & Run All' command from the menu. Save it.
    Export the notebook as HTML as well, and save the file in the repo.
    Do not forget to commit/push all the changes to your repo on hithub.
    Smile :) You did a good job!

FAQ:

    Can I take a look at different solution provided at kaggle? Yes, you can. But check more than one solution. Try to understand what the authors are trying to solve, and how could it be used in your project. Try to find really good examples - easy to understand and not so complicated. Remember - you create the notebook as an instruction to someone else! Try to not complicate the process.
    Can I take a look at my friend's solution, that he/she has just put on github? Yes, you can. But it's the smart way of solving the project. I'm sure that you want to be smarter in the next semester - so try to create a better solution and your own one :)
    Jupyter notebook provide R kernel, so can I use R instead? Nope, R sucks. Even if you love R, try to solve the project using Python.


    ```
