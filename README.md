IMPORTANT - PLEASE READ:

Beginning on November 4, 2019, I will NO LONGER support people that have downloaded the source
as a zip file. Using git has much more flexibility. In addition, there is much less liklihood
that a user will contact me with a problem that is ALREADY fixed.

If your system says that /lib/modules/...../build does not exist, you have not
installed the kernel headers, you have done it incorrectly, or you are not running
the kernel for which the headers have been installed. The necessary steps are
dependent on which distro you are using. Creating a new issue and asking at
GitHub will not be productive.

Unsolicited E-mail sent to my private address will be ignored!!

If a build fails that previously worked, perform a 'git pull' and retry before
reporting a problem. As noted, if you had downloaded the source in zip form, then you would
need to get an entirely new source file. That is why using git, which downloads only the changed
lines, is required.

rtl8192cu
=========

Repository for the stand-alone RTL8192CU driver.

Compiling & Building
---------
### Dependencies
To compile the driver, you need to have make and a compiler installed. In addition,
you must have the kernel headers installed. If you do not understand what this means,
consult your distro.
### Compiling

> make all

### Installing

> sudo make install

