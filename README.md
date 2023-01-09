# obieze
phishing tool
√] Description :

Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.

[+] Installation
Install dependencies (git, python, php ssh)

    For Debian (Ubuntu, Kali-Linux, Parrot)
        sudo apt install git python3 php openssh-client -y
    For Arch (Manjaro)
        sudo pacman -S git python3 php openssh --noconfirm
    For Redhat(Fedora)
        sudo dnf install git python3 php openssh -y
    For Termux
        pkg install git python3 php openssh -y

Clone this repository

    git clone https://github.com/obieze1/obieze
    
  Enter the directory

    cd obieze
Install all modules

    pip3 install -r files/requirements.txt

Run the tool

    python3 obieze.py

Or, directly run

wget https://raw.githubusercontent.com/obieze1/PyPhisher/main/obieze.py && python3 obieze.py



    pip3 install obieze [For Termux]
    sudo pip3 install obieze [For Linux]
    obieze

Docker

    sudo docker pull obieze1/obieze
    sudo docker run --rm -it obieze1/obieze

Support
OS 	Support Level
Linux 	Excellent
Android 	Excellent
iPhone 	
usage: pyphisher.py [-h] [-p PORT] [-o OPTION] [-t TUNNELER]
                    [-r REGION] [-s SUBDOMAIN] [-u URL] [-m MODE]
                    [-e TROUBLESHOOT] [--nokey] [--noupdate]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  obieze's server port [Default : 8080]
  -o OPTION, --option OPTION
                        obieze's template index [Default : null]
  -t TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
                        [Default : Cloudflared]
  -r REGION, --region REGION
                        Region for ngrok and loclx [Default: auto]
  -s SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for ngrok and loclx [Pro Account]
                        (Default: null)
  -u URL, --url URL     Redirection url after data capture [Default :
  
  
    -m MODE, --mode MODE  Mode of PyPhisher [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checking [Default : False]


  
    
    
    
    
Features:

    Multi platform (Supports most linux)
    Easy to use
    Possible error diagnoser
    77 Website templates
    Concurrent 4 tunneling (Ngrok, Cloudflared, Loclx and LocalHostRun)
    Upto 8 links for phishing
    OTP Support
    Argument support
    Credentials mailing
    Built-in masking of URL
    Custom masking of URL
    URL Shadowing
    Redirection URL settings
    Portable file (Can be run from any directory)
    Get IP Address and many other details along with login credentials
Requirements

    Python(3)
        requests
        bs4
        rich
    PHP
    SSH
    900MB storage

If not found, php and python modoules will be installed on first run



!] Disclaimer

This tool is developed for educational purposes. Here it demonstrates how phishing works. If anybody wants to gain unauthorized access to someones social media, he/she may try out this at his/her own risk. You have your own responsibil
