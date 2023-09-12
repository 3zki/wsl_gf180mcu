# wsl_gf180mcu

GF180MCU development tools for Ubuntu 22 (WSL2)

```
./setup.sh
```

# Differences between Standard PDK

Construction is not finished yet.

* Fixed xschemrc
* Changed color scheme table in GF180MCU technology files
* Add non-public layers such as Nwell_Label in mcu7t5v0 standard cells
  * Change LVS rules to recognize Nwell_Label, LVPwell_Label and Pad_Label

* Minor changes to avoid Pcell bugs (will be removed after resolution)
  * You might have to install "pip install gf180"
* Add DRC/LVS/PEX menu
  * Magic LVS cannot recognize V5_XTOR therefore menu replaces "05v0" with "06v0" in source netlist
