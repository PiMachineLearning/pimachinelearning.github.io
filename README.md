# Not used anymore
The repository has migrated to `https://pimachinelearning.wip.la/simple`, and moved to a VPS instead of GitHub Pages.
# wheels
Wheels built by PiMachineLearning as a binary repository

## Installation
The default pip.conf (located at /etc/pip.conf) on a Raspberry Pi OS might look like
```
[global]
extra-index-url=https://piwheels.org/simple
```
To use these wheels, simply change it to 
```
[global]
extra-index-url=https://piwheels.org/simple https://pimachinelearning.github.io/simple
```
