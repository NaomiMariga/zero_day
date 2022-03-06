### Project using Vagrant and Virtual Box
Steps involved:
- Install Virtual box
	- get it [here](https://alx-intranet.hbtn.io/rltoken/gnDuZRjo-TxXIvnH4aAG5g)
- Install Vagrant
	- get it [here](https://alx-intranet.hbtn.io/rltoken/rTqEUgxwGx2C-11h6lLcQA)
	- Set up ubuntu following these instructions
	- Open cmd and run the following commands
	`vagrant box add ubuntu/focal64` Note:This takes time
	`vagrant init ubuntu/focal64`
	`vagrant plugin install vagrant-vbguest`
	`vagrant up`
	`vagrant ssh`

And BOOM!. You all set.
