# lava-test-shell
Extension to LAVA test shell utility on Yocto Project Automated Hardware Test for Embedded Linux Devices

Reference to https://github.com/Linaro/lava-dispatcher/tree/release/lava_dispatcher/lava_test_shell

This repo is an extension support on using Buildbot CI utilities

1. Init Buildbot-Worker (Board detection)
2. Broadcasting Hardware Info
    a. Kernel version
    b. Embedded Linux OS version
    c. Services Started
    d. Network interfaces. (IPv4, Subnet, Domain)
    e. Disk storage 
    f. Hardware info (USB, RAM, CPU, PCIE, WiFi, LAN, Bluetooth, etc)
    g. Other expansion
