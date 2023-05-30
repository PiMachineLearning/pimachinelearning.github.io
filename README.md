# wheels
Wheels built by PiMachineLearning as a binary repository

## Installation
The default pip.conf (located at /etc/pip.conf) on a Raspberry Pi OS might look like
```toml
[global]
extra-index-url=https://piwheels.org/simple
```
To use these wheels, simply change it to 
```toml
[global]
extra-index-url=https://piwheels.org/simple https://pimachinelearning.github.io/simple
```
