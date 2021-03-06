----
# Welcome to RDPCoin! #

----
## What is RDPCoin? ##
RDPC is a cryptocurrency to make the world a better place.

----
## Get it! ##

  - *dependencies*:
    - *general* - Java 8
    - *Ubuntu* - `http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html`
    - *Debian* - `http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html`
    - *FreeBSD* - `pkg install openjdk8`

----
## Run it! ##

  - click on the RDPC icon, or start from the command line:
  - Unix: `./start.sh`
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:6876/ in a browser

----
## Compile it! ##

  - if necessary with: `./compile.sh`
  - you need jdk-8 as well

----
## Troubleshooting the RRS (RDPCoin Reference Software) ##

  - How to Stop the RRS Server?
    - click on RDPC Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on BitBucket

  - Permissions Denied?
    - no spaces and only latin characters in the path to the RRS installation directory
    - known jetty issue

----
## Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder

----

## License
* This program is distributed under the terms of the Jelurida Public License version 1.1 for the Ardor Public Blockchain Platform.
