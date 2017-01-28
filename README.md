# Vagrant automated VM for QA Automation development

This image is an Ubuntu Desktop 16.04 LTS plus:
  -  Oracle Java 8
  -  maven,  ant  
  -  git, git-flow, subversion 
  -  eclipse, eclipse-egit, eclipse-maven, eclipse-testng
  -  IntelliJ
  -  testng 
  -  selenium stand alone server
  -  firefox, chromium, chromium-chromedriver
  -  groovy
  -  es and en languajes packs

Base image is: 
  *vagrant init bento/ubuntu-16.04*

Pre:
  -  Image is optimized for Virtual Box, but not restricted to
  -  Make sure ssh and VBox are in path
  -  Default configuration for VM es 8G RAM, 3 core, bidireccional clipboard, active GUI

HOW TO:
  -  vagrant plugin install vagrant-reload
  -  vagrant up
  
  - add SQL Developer 
    - go to http://www.oracle.com/technetwork/developer-tools/sql-developer/downloads/index.html
	- download Other Platforms .zip
	- sudo unzip sqldeveloper-*-no-jre.zip -d /opt/
	- chmod a+x /opt/sqldeveloper/sqldeveloper.sh
	- close session and logon
