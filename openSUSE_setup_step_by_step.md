# Setup xterm terminal

# Install miniconda

1. Download miniconda installer from conda.io
2. Check the hash: sha256sum <filename.sh>
3. Install Miniconda: bash <filename.sh>
 
# Install & setup git

1. zypper install git
2. git config --global user.name Your name
3. git config --global user.email youremail@domain.com
    
# Setup conda environments

1. Create environments: conda create --name Jupyter_env

# Setup environment for Jupyter

## Install packages

1. conda install pip (python will be installed)
2. conda install ipykernel (for jupyter)
3. conda install jupyterlab
