# Cloud Knife for Chef
Private kitchen for clouds

## Setup
- install ruby & bundle
- Install required gems: `$ bundle install`
- Install vendor coockbooks: `$ librarian-chef install`
- install vagrant

## Install Vagrant
1. Install vagrant from gem deprecated. Go to [Vagrant Docs](http://docs.vagrantup.com/v2/installation/index.html) for instructions.
2. Setup Vagrant Box - *not required. At first run, box will be fetched automaticaly.*

       $ vagrant box add precise64 http://files.vagrantup.com/precise64.box
       
## Manage vendor coockbooks
The full specification for which third-party, publicly-released cookbooks your infrastructure repository depends will be in `Cheffile`. See: [Librarian-Chef](https://github.com/applicationsonline/librarian-chef#readme)


