# wsl_gf180mcu

GF180MCU development tools for Ubuntu 22 (WSL2)

```
git clone https://github.com/3zki/wsl_gf180mcu
cd wsl_gf180mcu
./setup.sh
```

# Differences between Standard PDK

Under construction...

* Fixed xschemrc
* Changed color scheme table in GF180MCU technology files
* Added undefined but used layers such as Nwell_Label in mcu7t5v0 standard cells
  * Changed LVS rules to recognize Nwell_Label, LVPwell_Label and Pad_Label

* Fixed Pcells to support the latest GDSFactory

* Add DRC/LVS/PEX menu
  * Magic LVS cannot recognize V5_XTOR therefore menu replaces "05v0" with "06v0" in source netlist
