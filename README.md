# homebrew-nrf5-tools

This repository contains the [nrf5 SDK](https://www.nordicsemi.com/DocLib/Content/SDK_Doc/nRF5_SDK/v15-3-0/index) compatible GNU Toolchain for ARM Embedded Processors as formulae for [Homebrew](http://brew.sh).

## About

This is a homebrew binary repository for the pre-built GNU toolchain from ARM Cortex-M & Cortex-R processors (Cortex-M0/M0+/M3/M4/M7/M23/M33, Cortex-R4/R5/R7/R8 and more).


## Installing the formulae

First `brew tap leojrfs/nrf5-tools` and then `brew install <formula>`.

### Using the prebuilt binaries

To install the entire ARM toolchain, do:

``` {.bash}
# to tap the repository
$ brew tap leojrfs/nrf5-tools
# to install the toolchain
$ brew install nrf5-sdk-arm-gcc-bin
```

## Docs

-   `brew help`, `man brew`, or the Homebrew [wiki](http://wiki.github.com/mxcl/homebrew).
-   [GNU ARM Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/)
