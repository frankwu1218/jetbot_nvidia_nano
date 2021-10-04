# alexnet
example to show to load alexnet on gpu on jetson nano

```
git clone https://github.com/lbaitemple/alexnet
cd alexnet
```
You can open alexnet_example.ipynb and run the code



##### if invalid load key, 'v'. when run the code

##### if git lfs install to 'lfs' is not a git command. See 'git --help'.
It looks like you haven't downloaded git-lfs on your machine, so git lfs install isn't a registered command by git.  
Install git-lfs as outlined below:  
1. Pre-Requisites. 
git-lfs requires git version 1.8.2 or later.  
You can check the version you have by running ```git --version```, and update if required.  
If you are installing on macOS, make sure you have Homebrew installed.  

2. Download
Download git-lfs by following the steps based on your operating system.

Debian / Ubuntu. 
```
$ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash. 
$ sudo apt-get install git-lfs
```
MacOS (Using Homebrew). 
```
$ brew update
$ brew install git-lfs
```
Windows. 
Download and run the latest windows installer.

3. Install
Finally, run ```git-lfs``` install to install ```git-lfs``` on your system.  
You can always run ```git-lfs uninstall``` to uninstall.

later. 
```
cd alexnet
git lfs install 
git lfs fetch 
git lfs pull
```
retry the code alexnet_example.ipynb.  
