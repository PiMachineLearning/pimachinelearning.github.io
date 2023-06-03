# staging
Wheels built by PiMachineLearning as a binary repository. This repository is the staging repository, which ensures some stability on the main repository. New wheels get pushed here instead of the main repository, so that the main repository does not recieve broken wheels.

## Installation
The default pip.conf (located at /etc/pip.conf) on a Raspberry Pi OS might look like
```
[global]
extra-index-url=https://piwheels.org/simple
```
To use these wheels, simply change it to 
```
[global]
extra-index-url=https://piwheels.org/simple https://pimachinelearning.github.io/staging/simple
```
