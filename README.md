![Author](https://img.shields.io/badge/author-Leviathan36-purple.svg)
![Release](https://img.shields.io/badge/release-beta-orange.svg)
![Language](https://img.shields.io/badge/made%20with-Jupyter%20Notebook-brightgreen.svg)
![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![LastUpdate](https://img.shields.io/badge/last%20update-2019%2F09-yellow.svg)

![logo](https://github.com/Leviathan36/MartianHacks/blob/master/IMAGES/logo.png)
# About

MartianHacks is a jupyter notebook  which contains the main commands executed during a penetration test.

The jupyter notebooks allow you to execute commands individually and collect the relative output in a very organized manner.
The python notebooks also make the transition from the commands execution to final report much easier.

It's possible to execute the notebook in a local server and, consequently, attack the machines on the LAN or execute it in a remote server and attack public IP.
In this last scenario, it's convenient exploit Google Colab service to use the powerfull hardware offered by Google (Tesla K80); in particulary, this is desirable for the password cracking phase.

# Tools
This jupyter notebook will install the following tools:

- Nmap
- Dirb
- Nikto
- Searchsploit
- hashcat
- xmllint

Also, several wordlists will be downloaded:

- URLs for http enumeration
- common web file extensions
- fasttrack.txt
- rockyou.txt

# Screenshots

Collect nmap output directly under the command execution instead of copying the result into a text editor.

![nmap_execution](https://github.com/Leviathan36/MartianHacks/blob/master/IMAGES/SCREENSHOTS/nmap_execution.png)
<br>

Explore the evidences collected with the **Table of contents** at the right side of the window.
<br>

![searchsploit_execution](https://github.com/Leviathan36/MartianHacks/blob/master/IMAGES/SCREENSHOTS/searchsploit_execution.PNG)
<br>
<br>

Look the root content with the tab **Files**.
Click on text files to open them (click on their icon for downloading).

<p align="center"><img src="https://github.com/Leviathan36/MartianHacks/blob/master/IMAGES/SCREENSHOTS/tab_files.PNG" width="75%" height="auto" alt="tab_files"></p>
<br>
<br>

# Disclaimer:
Author assume no liability and are not responsible for any misuse or damage caused by this program.

MartianHacks is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

# License:
MartianHacks is released under GPLv3 license. See [LICENSE](LICENSE) for more details.
