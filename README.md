# Development on Sun Devil Rocketry Linux Data Acquisition Driver
This repository will hold a drive for a Linux userspace driver to acquire data from SDR hardware.

Currently, there isn't much here - this is just a demo code structure. More to follow soon.

## Building and Running
1. Initiate the builddir by running the following in the root of the project directory:

```meson setup builddir``` 

(Or replace ```builddir``` with whatever you want to call it; ```builddir``` is preferred because that's what's in our gitignore.)
>[!Note]
>If you have to modify the build files, you may have to run ```meson setup builddir --reconfigure```
2. Build the code

```meson compile -C builddir```

3. Run it

```builddir/linux-device-driver```