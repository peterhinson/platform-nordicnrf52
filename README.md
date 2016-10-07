# [Nordic nRF52](https://www.nordicsemi.com/eng/Products/nRF52-Series-SoC): development platform for [PlatformIO](http://platformio.org)

Nordic nRF52832 platform for PlatformIO. Currently supports mbed and defines a board type for the pca_10040 development kit. Fantastically limited testing!

Based off of the PlatformIO Nordic nRF51 package:
* [Nordic nRF51 on PlatformIO](http://platformio.org/platforms/nordicnrf51) (home page in PlatformIO Platform Registry)
* [Nordic nRF51 Documentation](http://docs.platformio.org/en/stable/platforms/nordicnrf51.html)

# Usage

1. [Install PlatformIO CLI](http://docs.platformio.org/en/stable/installation.html)
2. Install Nordic nRF52 development platform:
```bash
# install development version
> platformio platforms install https://github.com/peterhinson/platform-nordicnrf52.git
```

# TODO
* JLink support
* nRF SDK support in addition to mbed
* Testing!