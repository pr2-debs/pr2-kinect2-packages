# pr2-kinect2-packages
The following debian package will run a script which will install the packages required to use Kinect 2 in your ROS environment using an Intel HD Graphics Card.

## Intructions
Before installing please add the beignet ppa into your repo list by:
```
sudo add-apt-repository ppa:pmjdebruijn/beignet-testing
sudo apt-get update
```
Please add your computer's IP address and hostname to the NUC's /etc/hosts file then add the NUC's IP address and hostname (pr2-head) to your own /etc/hosts file.
