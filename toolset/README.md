# DSEtoolset


## Table of Contents

  - [Installation](#installation)
  - Operational Systems
    - [Linux Ubuntu](#ubuntu)
  - Integrated Development Environments (IDE)
    - [Anaconda](#anaconda)
    - [PySharm](#pysharm)
    - [Atom](#atom)
    - [Vim](#vim)
    - [RStudio](#rstudio)
  - [Bash Scripting / Command Line](#bash)
  - [Python virtual environments](#virtualenv)
    - [PipEnv](#pipenv)
    - [VirtualEnv](#virtualenv)
    - [PyEnv](#pyenv)
    - [Conda](#conda)
  - [Version control & repository systems](#git)
    - [Github cheat-sheet](github-cheat-sheet)
    - [Introduction to Git & Github RG](github)
  - [DevOps](devops)
  - Virtualization - Containerization
    - [Docker](docker)
  - Collaboration tools
    - [Slack](#slack)
    - [Zoom](#zoom)
  - Presentation tools
    - [Google Slides](#google-slides)
  - Resources
  - [Links](#resources)

## Installation

##  Operational Systems

## Ubuntu

https://arstechnica.com/information-technology/2018/05/ubuntu-18-04-the-return-of-a-familiar-interface-marks-the-best-ubuntu-in-years/

[Ubuntu 18.04: What's New?](https://www.youtube.com/watch?v=ONXfL6evR0Q)
[10 Reasons why Linux is Better Than MacOS or Windows](https://www.youtube.com/watch?v=qH3v41JmyIg)
[How to install Ubuntu 18.04 Bionic Beaver](https://linuxconfig.org/how-to-install-ubuntu-18-04-bionic-beaver)
[How to create a bootable Ubuntu 18.04 Bionic USB stick on   Linux](https://linuxconfig.org/how-to-create-a-bootable-ubuntu-18-04-bionic-usb-stick-on-linux)                    
[The Complete Linux Course: Beginner to Power User!](https://www.youtube.com/watch?v=wBp0Rb-ZJak)
[Ubuntu Cheat Sheets](https://www.cheatography.com/tag/ubuntu/)

[10 Free Linux Productivity Apps You Haven’t Heard Of](https://www.youtube.com/watch?v=dxaXrFH-8Ek)
https://www.maketecheasier.com/free-linux-productivity-apps-you-havent-heard-of/

## MacOS

## Windows

##  Integrated Development Environments (IDE)
##  Anaconda

[Jupyter notebook, JupyterHub, JupyterLab](http://jupyter.org/)

[Nbviewer](https://nbviewer.jupyter.org/)

[Apache Zeppelin notebook](https://zeppelin.apache.org/)

##  PyCharm
[PyCharm](https://www.jetbrains.com/pycharm/)

##  Atom
[Atom](https://atom.io/)

##  Vim
[VIM](https://www.vim.org/)

##  RStudio
[RStudio](https://www.rstudio.com/)

## Bash
###  Bash Scripting / Command Line is a way of interacting with your computer  operating system using text-based commands.

Bash Scripting

https://programminghistorian.org/lessons/intro-to-bash
https://linuxconfig.org/bash-scripting-tutorial

Command Line

https://www.computerhope.com/issues/chusedos.htm

## Python virtual environments and package management system
## PipEnv

Pip + VirtualEnv    https://docs.pipenv.org/

https://realpython.com/pipenv-guide/  https://github.com/pypa/pipenv

https://opensource.com/article/18/2/why-python-devs-should-use-pipenv

https://feici02.github.io/2017/09/24/pipenv-cheatsheet.html


## PipEnv from Scratch
https://github.com/daneah/pipenv-tutorial

https://github.com/daneah/pipenv-tutorial/blob/master/cheatsheet.md



### VirtualEnv

Python virtualenv Ubuntu
```
$ sudo pip install virtualenv myenv    # if error   sudo apt install python-pip
$ sudo apt-get update
$ virtualenv myenv
$ source myenv/bin/activate          # deactivate
```

http://docs.python-guide.org/en/latest/dev/virtualenvs/

https://virtualenv.pypa.io/en/stable/
https://packaging.python.org/guides/installing-using-pip-and-virtualenv/

### PyEnv
[PyEnv](https://github.com/pyenv)


## Conda
https://conda.io/docs/ https://www.anaconda.com/download/

https://conda.io/docs/user-guide/getting-started.html
https://conda.io/docs/user-guide/tasks/manage-environments.html

```
$ conda create --name python37
$ activate python37
$ conda install pandas
$ deactivate
```
### Create a virtual environment with specific version
```
$ create --name mypython3version python=3.5
```
### Create a virtual environment with specific version and a single module
```
$ create --name mypython3version python=3.5 numpy
```
### Create a virtual environment with specific version with entire Anaconda distribution
```
$ create --name mypython3version python=3.5 anaconda
```
### To check the environments
```
$ conda info --envs
```

## Version control and repository systems
## Git

[Git](https://git-scm.com/)
[Github](https://github.com/)
[Gitlab](https://gitlab.com/)
[Bitbucket](https://bitbucket.org)

* [Github cheat-sheet](github-cheat-sheet)
* [Introduction to Git & Github RG](github)
* [Udacity's course How to Use Git and GitHub](udacitygitgithub)
* [Github template](github-template)



##  Containerization - Virtualization



## VM VirtualBox Oracle

## Vagrant

##  Docker



##  Collaboration tools

## Slack
https://dseclub.slack.com

https://join.slack.com/t/dseclub/shared_invite/enQtMjQxNTI1NDI3MjQ4LTFlZTA0NjVlNzNiMzI0MmY0YWJkNjMwYTZiY2NmMGJkMWM5NDExZTgyZTdhYzQ4NWZlYzFkNDI3ZmZjZTAyMDA

## Zoom
https://www.zoom.us/
https://blogs.otago.ac.nz/zoom/how-to-join-a-zoom-meeting-step-by-step/

## Skype
https://www.skype.com/en/

##  Presentation tools
##  Google Slides
[Google Slides](https://docs.google.com/presentation/u/0/)

##  jupyter notebook

## Resources
https://www.ngdata.com/top-tools-for-data-scientists/
