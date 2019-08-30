# RL_AV
If you are curious about reinforcement learning, you might find some information that is useful for you.

## Clone the Repo:
Run in terminal:  
`mkdir ~/no_backup`  
`cd ~/no_backup`      
`git clone https://github.com/kaya2016/RL_AV.git`      

## Create a Virtual Environment
First, we create a virtual environment where we want to put all the required packages. 

1. Create a Python 3 virtual environment  
`virtualenv ~/no_backup/venv_ml -p python3.5`

2. Activate the virtual environment by running the command  
`source ~/no_backup/venv_ml/bin/activate`

3. Install the required packages   
`pip3 install -r requirements.txt` 

4. Show a list of all installed packages  
`pip3 list --local`

5. install the activated environment as an ipython kernel  
`ipython kernel install --user --name=venv_ml`

6. Deactivate the environment, When you finish your work   
`deactivate`
