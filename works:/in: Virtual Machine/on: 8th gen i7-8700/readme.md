# celadon-binary
works: True!
Host: Ubuntu 22.04

image:
- version: CIV_00.23.04.51_A14
- download url: https://github.com/projectceladon/celadon-binary/tree/master/CIV_00.23.04.51_A14

setup: `sudo -E ./scripts/setup_host.sh`

vm-manager:
- run: `sudo vm-manager -b civ-1`
- graphics: `type=virtio`
