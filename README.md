This repo and subsequent port is not yet included in Contiki OS.  This is as of now a third-party effort.  The idea of this stripped version comes from the CC13xx port of Contiki. 
As of now, this repo is not affiliated with Contiki OS, but will hopefully be integrated when complete.

This is a git-versioned subset and slightly modified version of ST's STM32CubeF1.

This repository's sole purpose is to provide stm32cubef1 as a submodule for the [Contiki Operating System](https://github.com/contiki-os/contiki/).

New versions will only appear in this repository only if and when Contiki's STM32F1 port needs to use them.

Modifications (for current and upcoming versions):

* Only files used by Contiki are included here. Documentation and files related to other toolchains except GCC have been removed.

BSPs and some Middleware files have been removed.  These files may be re-included if Contiki requires these files for any new platform.

All sources are and will remain otherwise intact, except in case where modifications are required by Contiki.

[STM32CubeF1](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32cube-embedded-software/stm32cubef1.html) is distributed by ST. If you are looking for the latest version of STM32CubeF1, do not clone this repository.

Do not open pulls / issues on this repository, unless they are immediately related to using STM32F1 with Contiki.