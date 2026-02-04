ts@aerynos:~/Pobrane

$ moss index .

Indexing 1 files

Indexed nouveau-firmware-custom-1.0.0-8-1-x86_64.stone

Index file written to "/home/ts/Pobrane/stone.index"

ts@aerynos:~/Pobrane

$ sudo moss repo add local-custom file:///home/ts/Pobrane/stone.index

local-custom added

ts@aerynos:~/Pobrane

$ sudo moss sync

No packages to sync

ts@aerynos:~/Pobrane

$ sudo moss install nouveau-firmware-custom

The following package(s) will be installed:


nouveau-firmware-custom  1.0.0-8

✔  Do you wish to continue?  · yes

Installed nouveau-firmware-custom


85138 entries blitted in 13.41s (6.3k / s)
