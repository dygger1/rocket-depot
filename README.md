#### Rocket Depot
Rocket Depot is a simple graphical frontend for [rdesktop](http://www.rdesktop.org/) and [FreeRDP](http://www.freerdp.com/) with
support for connection profiles.  It runs on Linux desktops using GTK+ 3 and
takes advantage of modern desktop environment features such as Unity
Quicklists.

![screenshot-main.png](screenshot-main.png "Screenshot")

![screenshot-quicklist.png](screenshot-quicklist.png "Screenshot")

#### Installation

##### [Arch Linux](https://aur.archlinux.org/packages/rocket-depot-git/)
    git clone https://aur.archlinux.org/rocket-depot-git.git
    cd rocket-depot-git
    makepkg -si

##### [Debian Jessie](http://packages.scottlinux.com/)
    wget -O - http://packages.scottlinux.com/robled.gpg.key | sudo apt-key add -
    echo 'deb http://packages.scottlinux.com/ jessie main' | sudo tee /etc/apt/sources.list.d/rocket-depot.list
    sudo apt-get update && sudo apt-get install rocket-depot

##### [Fedora](https://copr.fedorainfracloud.org/coprs/robled/rocket-depot/)
    sudo dnf install rocket-depot

##### [Ubuntu Trusty/Wily](https://launchpad.net/~robled/+archive/rocket-depot)
    sudo apt-add-repository ppa:robled/rocket-depot
    sudo apt-get update
    sudo apt-get install rocket-depot

##### [PyPI](https://pypi.python.org/pypi/rocket-depot)
    sudo pip install rocket-depot
Install the following packages for your distro:
* pygobject3 
* hicolor-icon-theme 
* xterm 
* freerdp 
* rdesktop

#### [Changelog](https://github.com/robled/rocket-depot/blob/master/CHANGES.txt)
