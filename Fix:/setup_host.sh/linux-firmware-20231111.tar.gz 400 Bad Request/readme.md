# linux-firmware-20231111.tar.gz Fails to download
from: "sudo -E ./scripts/setup_host.sh"

## Error: Line 209
`/scripts/setup_host.sh Failed at line(209): wget "https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/snapshot/linux-firmware-20231111.tar.gz" -P $CIV_WORK_DIR`

## Cause:
This file has been removed on Server!

# Solution:
Get from alternate location:
```
wget -c https://www.kernel.org/pub/linux/kernel/firmware/linux-firmware-20231111.tar.gz
```

more:
- sch: https://www.google.com/search?q=linux-firmware-20231111.tar.gz
