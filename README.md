# tickets + bugs

| ticket | description |
| :--- | :--- |
| formatting | To do the computer formatting, I downloaded the Ubuntu Desktop .iso image from [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop) and burn this image in a USB drive using the **Startup Disk Creator** software, already available in old Ubuntu \(I also discovered a online way to do it: [FlashOS](https://www.balena.io/etcher/)\). Then, using **F12** key, I accessed the BIOS setup and I was able to boot from USB driver. The rest concerns on setups of the OS and it is easier. |

| bug | solution |
| :--- | :--- |
| non-zero status in R | There are missing some libraries. The missing libraries names appears in the Error Message in R. To solve, it is enough to install these libraries on the system via bash. For examplo, if the missing one is libcurv4.deb, use `sudo apt install libcurl4.deb` |

