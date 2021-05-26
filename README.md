# YoctoBeaglebone
Beaglebone distro build using Yocto

#### Install repo

	# curl https://storage.googleapis.com/git-repo-downloads/repo > /usr/local/bin/repo
	# chmod a+x /usr/local/bin/repo


#### Get project

	repo init -u git@github.com:sergiineodnichyk/beaglebone-manifest.git -b master
	repo sync -c

#### Build project

From project root folder use make help for detailes.

#### Yocto required

    # apt-get install gawk wget git-core diffstat unzip texinfo gcc-multilib build-essential chrpath socat libsdl1.2-dev xterm
