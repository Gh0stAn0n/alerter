# About 'alerter'

<p align="center">
   </a>
      <a href="https://github.com/Gh0stAn0n/alerter">
      <img src="https://img.shields.io/badge/Version-1.0.0-darkgreen">
        <img src="https://img.shields.io/badge/Release%20Date-april%202022-purple">
  <img src="https://shields.io/badge/Platform-Linux-darkred">
    </a>
  </p>
</p>

alerter is a honeypot program that allows users to create and manage SSH, FTP, and Telnet services using the Twisted engine for Python 3. The program stores all credentials on a local MySQL database and provides a monitoring tool to track all attacker attempts in real-time.

With Alerter, users can easily detect suspicious activity on their services and take appropriate measures to protect their network. The program's monitoring tool provides valuable information such as the service being targeted, IP address of the attacker, their country of origin, username and password attempted, which can be used to create comprehensive dictionaries for use in pentesting.

### Possibility and Capability

>ADVANTAGES:

- help and info menu doesn't require sudo privileges.

- have 3 way to analyze the wanted file: 1=standard bash script, 2=argument script, 3=flag script (using arguments)

- capable of doing almost every volatility commands since not every one of them use the same option. (if your suggested profile is for exemple VistaSP1x86, some command could require for exemple WinSP2x86)

- will save the user general scans in a statistics file.

- check if the new supposed output file or directory is already created. (instead of :: error cant write on 'file.txt' because 'file.txt' already exist :: you'll get file.2.txt or dir.2 then .3, .4, ect...)

- check for every errors possible. (correct path, correct answers as input, if the mem file choosen is truly a mem file)

- the required dependencies and libraries will be scanned and any missing packages will be installed automatically.

>DISADVANTAGES:

- since we can run the script using arguments and flags, we cant put errors message for the flags option using "else" because it will disable the arguments scipt and vice versa.

- if incorrect arguments or flags are written, the standard script will run. (advantage as well)

### 'analyzer' Project

a [project](https://github.com/Gh0stAn0n/alerter/files/9894648/project.pdf) made by [ThinkCyber](https://www.thinkcyber.co.il/).

### Video Demonstration

Be Aware: the script could be different from the video since he got upgraded.

### Download

    git clone https://github.com/Gh0stAn0n/alerter /opt/alerter && cd /opt/alerter

### Script Usage

launch the script by typing:

└─$ sudo bash setup

└─$ sudo ./alerter

-h (stand for help) for more info about the flags option.

-i (stand for info) for more info about the script.
