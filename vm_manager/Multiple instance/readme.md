# Multiple instances are Possible!
requires: multiple /opt/civ-{n} folders, and multiple ~/.intel/.civ/civ-{n}.ini files!

Inside each `civ-{n}.ini` change all variables to match the instance number!
- `civ-1` becomes `civ-{n}`

Start each:
```
sudo vm-manager --start civ-1
sudo vm-manager --start civ-2
```

Stop each:
```
sudo vm-manager --stop civ-1
sudo vm-manager --stop civ-2
```

example:
- /opt/civ-1
- /opt/civ-1
- ~/.intel/.civ/civ-1.ini
- ~/.intel/.civ/civ-2.ini
