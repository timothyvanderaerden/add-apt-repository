# add-apt-repository
Easily add repositories from launchpad for Debian systems.

## Dependencies
  - apt
  - apt-key

## Installation
  1. Download or clone this repository
  
  ```
    git clone git@github.com:timothyvanderaerden/add-apt-repository.git
  ```
  
  2. Make the script executable
  
  ```
    chmod +x ./add-apt-repository
  ```
  
  4. (optional) Use it as a global command
  
  ```
    sudo mv add-apt-repository /usr/bin
  ```
  
## Usage

  ```
    sudo ./add-apt-repository ppa:user/package
  ```
  The script will automaticly take the package for xenial. You can change this:
  ```
    sudo ./add-apt-repository ppa:user/package zesty
  ```  
