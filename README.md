# wsl_gf180mcu

GF180MCU development tools for Ubuntu 22 (WSL2)

```
./setup.sh
```

# Differences between Standard PDK

* Changed color scheme table in GF180MCU technology files
* Add non-public layers such as Nwell_Label in mcu7t5v0 standard cells
* Change LVS rules to recognize Nwell_Label and LVPwell_Label
* Minor changes to avoid Pcell bugs (will be removed after resolution)
* Add DRC/LVS/PEX menu
  * Magic LVS cannot recognize V5_XTOR therefore menu replace "05v0" with "06v0" in source netlist.
