# ipfs-systemctl

Systemctl script to automatically start the daemon on boot.

## Predepends
 - ipfs
 - systemctl

## Installation

1. Modify `ipfs.service` and include your User and Group. Mine is there by
   default.
2. Run the below steps.
```
sudo ./install.sh
sudo systemctl enable ipfs
sudo systemctl start ipfs
```
