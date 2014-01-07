## View write protect status

    $ cat /sys/kernel/mmc_protect/status

## Set write protect

    $ echo -n "mmcblk0p15" > /sys/kernel/mmc_protect/set

## Clear write protect

    $ echo -n "mmcblk0p15" > /sys/kernel/mmc_protect/clear
