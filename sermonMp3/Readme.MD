# Sermon Uploader
Automates the steps required to publish a recorded WAV as compressed MP3 on remote FTP server. Comes with a simple UI to control the process.

## Installation
1. Install a Java Runtime Environment (JRE). E.g from AdoptOpenJDK: https://adoptopenjdk.net/
1. Download and install the Filezilla Client for FTP uploads: https://filezilla-project.org/download.php
1. Download and unpack this repository to a directory of your choice: https://github.com/ivy-rew/misc/archive/master.zip
1. Edit the ant.properties file to match your runtime environment

## Troublshooting
1. Basically the tool is platform independent. However when working with Windows take care on the directory path separators provided in the ant.properties file. Either use single forward slashes or double backward slashes.

## Environment
- Tested with Java 1.8 LTS and Windows 7.
