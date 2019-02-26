# ULMFit
An Implementation of [ULMFit](http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html)

# Downloading Data 
[Twitter US Sentiment Data](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) can be downloaded via the site. 

# Usage 
'twitter_data_exploration.ipynb' gives you a nice overview of the data exploration 
and an implementation of ULMFit to obtain an accuracy of <b>62%</b>

# Setting up Environment
A detailed overview is provided by Jeremy Howard in the [fastai forum](https://forums.fast.ai/t/fastai-v0-7-install-issues-thread/24652)

On Mac:
1. Open Terminal
2. Navigate to desired folder:            cd "~\path\folder"
3. Clone fastai repository from GitHub:   git clone https://github.com/fastai/fastai.git
4. Navigate to cloned repository:         cd fastai
5. Create environment:                    conda env create -f environment-cpu.yml
6. Activate environment:                  conda activate fastai-cpu
7. Start Jupyter Notebook: jupyter notebook

On Windows: 
The Prompt console must be runned as an administrator.
Commands must be run in the Anaconda Prompt console. 
