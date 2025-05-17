# linux-firmware-20231111.tar.gz Fails to download
from: "sudo -E ./scripts/setup_host.sh"

# Cause:
This file has been moved!

# Solution:
Get from alternate location:
```
wget -c https://www.kernel.org/pub/linux/kernel/firmware/linux-firmware-20231111.tar.gz
```

more:
- sch: https://www.google.com/search?q=linux-firmware-20231111.tar.gz
