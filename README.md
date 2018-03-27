# ubunturepo

## modifications made here will not survive a re-bundle.
## if you wish to make changes you can:
## a.) add 'apt_preserve_sources_list: true' to /etc/cloud/cloud.cfg
##     or do the same in user-data
## b.) add sources in /etc/apt/sources.list.d
## c.) make changes to template file /etc/cloud/templates/sources.list.tmpl

# See http://help.ubuntu.com/community/UpgradeNotes for how to upgrade to
# newer versions of the distribution.
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial main restricted
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial main restricted

## Major bug fix updates produced after the final release of the
## distribution.
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates main restricted
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates main restricted

## N.B. software from this repository is ENTIRELY UNSUPPORTED by the Ubuntu
## team. Also, please note that software in universe WILL NOT receive any
## review or updates from the Ubuntu security team.
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial universe
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial universe
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates universe
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates universe

## N.B. software from this repository is ENTIRELY UNSUPPORTED by the Ubuntu
## team, and may not be under a free licence. Please satisfy yourself as to
## your rights to use the software. Also, please note that software in
## multiverse WILL NOT receive any review or updates from the Ubuntu
## security team.
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial multiverse
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial multiverse
deb http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates multiverse
deb-src http://ap-south-1.ec2.archive.ubuntu.com/ubuntu/ xenial-updates multiverse

## N.B. software from this repository may not have been tested as
## extensively as that contained in the main release, although it includes
## newer versions of some applications which may provide useful features.
## Also, please note that software in backports WILL NOT receive any review
## or updates from the Ubuntu security team.
