# Panda Linux
Open Source Linux Operating System

*Note: Currently under development. Use it on your own risk.*

Installation
------------

Before starting the installation for your system, execute the following steps:

*Note: Execute the following steps after downloading the packages.*
- Extract `GCC`, `MPFR`, `MPC` and `GMP`.
- Create new directories inside `src/pkg/gcc-5.2.0` as `mpfr`, `mpc` and `gmp`.
- Copy data from the extracted directories into the newly created directories.
- Compress the `gcc-5.2.0` folder as `gcc-5.2.0.tar.bz2`

Make `install` executable
```
chmod +x install
```
Run the `install` file
```
./install <mountPoint>
```
Here `mountPoint` is the path to an empty partition with minimum 10 GB of space. This partition should contain `ext4` filesystem.
