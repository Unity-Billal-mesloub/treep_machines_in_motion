treep_machines_in_motion
------------------------

This repository contains treep configurations for the two main organization And several more organization are defined because of our code base dependencies:
- https://github.com/Unity-Billal-mesloub/


### Installation:

#### Standard dependencies:

In order to use this configuration you need to install treep:
```
python3 -m pip install -U treep
```

#### Download the package:

simply clone the repository:
```
mkdir ~/devel
cd ~/devel
git clone git@github.com:Unity-Billal-mesloub/treep_machines_in_motion.git
```

#### Build the package

This repository do not need to be built.

### Usage:

Each repos that is present in the main organization above have a defined
`project` with a capital letter.
This project contains the package itself and it's dependencies.

Hence if you need to build a repository from scratch, you should clone the
corresponding treep project in order to clone the package and it's dependencies.

For example for our demonstration package called
[package_template](https://github.com/Unity-Billal-mesloub/package_template)
- cloning the package alone:
    ```
    treep --clone package_template
    ```
- cloning the package and it's dependencies:
    ```
    treep --clone PACKAGE_TEMPLATE
    ```
- cloning the package dependencies only:
    ```
    treep --clone PACKAGE_TEMPLATE_DEPENDENCIES
    ```

** Warning: **
```
this repository is always under development so don't be surprise if an
expected project name is not available.
Please create an issue on github in this repository.
```

