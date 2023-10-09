# breast-cancer-prediction-ml-project

# First we Create instance with ubuntu AMI with t2.medium instance type with 30GB storage 


sudo apt-get update && sudo apt-get upgrade -y      
sudo apt install python3-venv -y          (install python environment)
python3 -m venv MLPRO
source MLPRO/bin/activate                 (activate env)
mkdir mlproject                           (create one project directory)
cd mlproject                              (enter in project directory)

# Login to your github account and create a new repo and paste cmds from github repo:

echo "# End-to-end-ML-Project" >> README.md
git add README.md
git commit -m "First Commit"
git status
git branch -M main
git branch
git remote add origin https://github.com/vipulwarthe/mlproject.git
git push -u origin main
git remote -v    (additional command)

# Create .gitignore file with python template in mlproject repo on github

git pull    # It will pull the .gitignore file in VScode mlproject repo

# create setup.py and requirements.txt in mlproject repo add a code in setup.py & requirements.txt

# setup.py will be responsible in creating my ML application as a package
# setup.py is a module used to build and distribute Python packages
# requirements.txt file is a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project

pip install -r requirements.txt 
git status
git add .
git status
git commit -m "setup file added"
git push -u origin main
