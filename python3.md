# Installing Python3 
1. Confirm that you have pythin is installed on your machine using the command `python3 --version`
2. If Python is not installed or is not in the latest version you desire, then we move to this step. We now install all necessary prerequisite for adding the PPAs (Personal Package Archives).
3. We will begin by installing the **software-properties-common** package which will provide a tool called **add-apt-repository** This tool will be used to new package repositories to you PC's sources list. 
    a. `sudo apt install software-properties-common -y`
    b. `sudo add-apt-repository ppa:deadsnakes/ppa`
4. After adding the above packages, we then update our system and then install the desired version of Python:
    a. `sudo apt-get update`
    b. `sudo apt-get install python3.13`
 5. You can confirm the Python3 version installed using the command `python3 --version`
 