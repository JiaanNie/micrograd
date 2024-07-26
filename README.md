## installing anaconda and python3.12
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get install python3.12
alias python='python3.12'
sudo apt-get install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
curl -O https://repo.anaconda.com/archive/Anaconda3-2024.06-1-Linux-x86_64.sh
bash ./Anaconda3-2024.06-1-Linux-x86_64.sh
export PATH="/home/wilson/anaconda3/bin:$PATH"
conda info


##creating venv 

conda create --name <env-name>

conda env list

source activate base


conda activate ml-learning

conda deactivate


Note pip and conda both are package managercd 
## installing jupyter notebook
conda install jupyter

jupyter notebook --port=8889 --no-browser


## getting started with micrograd



setting up pytorch

- first install cuda sdk