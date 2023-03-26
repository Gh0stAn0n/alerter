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

alerter is an honeypot program that allows users to create and manage SSH, FTP, and Telnet services using the [Twisted](http://twistedmatrix.com/) engine for Python3.
The program stores all credentials on a local MySQL database and provides a monitoring tool to track all attacker attempts in real-time.

users can easily detect suspicious activity on their services and take appropriate measures to protect their network. The program's monitoring tool provides valuable information such as the service being targeted, IP address of the attacker, their country of origin, username and password attempted, which can be used to create comprehensive dictionaries for use in pentesting.

NOTICE: this program is the upgraded version of [twisted-honeypot](https://github.com/lanjelot/twisted-honeypots)

![monitor](https://camo.githubusercontent.com/9f44b1a8324f280000428b0e7b95446ef7752418b2fcbf884163c1335a5eb6a8/68747470733a2f2f692e696d6775722e636f6d2f3570344752357a2e706e67)

### Possibility and Capability

>ADVANTAGES:

- help and info menu doesn't require sudo privileges.

- the required dependencies and libraries will be scanned and any missing packages will be installed automatically.

- will set automatically the MySQL database if none exist.

- have 3 way to alert the network: 1=standard bash script, 2=argument script, 3=script prompt

- check for every errors possible. (correct path, correct input)

- troubleshooting guidance at [file]()

- could generate a pentest dictionnary based on the generated content from the attackers.

>DISADVANTAGES:

- none

### 'alerter' Project

a [project](https://github.com/Gh0stAn0n/alerter/files/9894648/project.pdf) made by [ThinkCyber](https://www.thinkcyber.co.il/).

### Video Demonstration

Be Aware: the script could be different from the video since he got upgraded.

### Download

    git clone https://github.com/Gh0stAn0n/alerter /opt/alerter && cd /opt/alerter

### Scripts Info

setup - set all relevant information to enable the programs.

start - start the honeypot.

stop - stop the honeypot.

restart - restart the honeypot.

monitor - monitor the honeypot.

reset - reset all data related to the previous honeypot sessions.


### Script Usage

launch the script by typing:

└─$ sudo ./setup

└─$ sudo ./alerter

-h (stand for help) for more info about the flags option.

-i (stand for info) for more info about the script.
