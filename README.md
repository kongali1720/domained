# Selamat Datang | WELCOME

# domained – Multi Tool Subdomain Enumeration Suite on Kali Linux

  Information Gathering is the crucial step in the process of penetration testing. 
  The more you collect the information the more it will help you to get a better testing methodology.
  So for this purpose of Information Gathering, the Domained tool is created. Domained is a framework collection of various subdomain detection tools. Domained is a python language-based tool that uses several
  subdomain enumeration tools and wordlists to create a unique list of subdomains passed to the EyeWitness tool for reporting with categorized snapshots, server response headers, and signature-based default
  credentials checking.
  Several tools are integrated with the Domained tool that covers the enumeration phase, reporting, and wordlists. Domained tools will allow the penetration tester to verify the target against different programs.

# Note: Make Sure You have Python Installed on your System, as this is a python-based tool. 

# Click to check the Installation process: Python Installation Steps on Linux Included Subdomain Enumeration Tools:

    Sublist3r
    enumall
    Knock
    Subbrute
    massdns
    Recon-ng
    Amass
    SubFinder

# Included Reporting and Wordlists:

    EyeWitness
    SecList (DNS Recon List)
    LevelUp All.txt Subdomain List

# Installation of Domained Tool in Kali Linux:

# Fire up your Kali Linux terminal and move to Desktop using the following command.

    $ cd Desktop
    $ mkdir Domained
    $ cd Domained
    $ sudo git clone https://github.com/TypeError/domained.git
    $ ls
    $ cd domained
    $ ls
    $ sudo pip install -r ./ext/requirements.txt
    $ sudo python3 domained.py --install
    $ python3 domained.py -h
    $ python3 domained.py -d geeksforgeeks.org
    $ python3 domained.py -d geeksforgeeks.org --quick --notify

