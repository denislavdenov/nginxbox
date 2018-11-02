## This repository is based on 
https://github.com/nabels-coolblue/packer-xenial64

# Purpose
This repository attempts to store the minimum amount of code that is required to create a nginx Ubuntu Xenial64 box

# How to use

## Need to install packer before creating this box

Fork the repo, enter `box` folder and do `packer build xenial64.json`

# Kitchen tests are included
## Install chefdk,rbenv 2.3.1 and vagrant
Run kitchen test after box is created in order to test if nginx is installed

```
gem install kitchen-vagrant
kitchen test
```
