# Installing latest version of Node
N.B. 
    a. The are several ways to install Node on your PC. However, using NVM(Node Version Manager) is the best and most realiable. Using NVM also allows use manage various versions of Node.js and their associated Node Packages at the same time. 
    b. The steps provided in here are to be run on your terminal. 
1. Ensure you have NVM installed in you PC using the command `nvm -v`
    - If you do not have NVM or you wish to upgrade the NVM version in you PC, follow the following steps:
        * Ensure your system is up-to date using the command `sudo apt update`
        * Download and install NVM using the command `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash`
            + Ensure that in the command above where the version is `v0.39.7` is replaced with the version of NVM you wish to have on your PC. 
        * You can check the NVM Version installed using the command `nvm -v`
2. With NVM installed, we will use bash to istall the Node version we want in our PCs. Before using bash, it is important to identify if the script will perform the work it is suppossed to do. We will use the command
    `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh` Keep in mind we are using the NVM version installed on our PCs. 
    Once there are no issues after the above command, we will use bash after the above command
    `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash` This command will install the NVM script into the PC user account
3. Having installed the desired NVM Script for our node, you have to access the PC `.bashrc` file using the command `source ~/.bashrc`
4. After accessing the above file, you can ask NVM on the Node versions that are available. To do this, use the command `nvm list-remote`
5. A list of the available node versions will be listed. Pick the version you wish to install on your machine and install it using the command
    `nvm install v20.14.0`
6. You can confirm the installed node verson using the command `nvm list`
