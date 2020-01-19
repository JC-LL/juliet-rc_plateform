```
               __     ___     __      ___  _____
           __ / /_ __/ (_)__ / /_____/ _ \/ ___/
          / // / // / / / -_) __/___/ , _/ /__
          \___/\_,_/_/_/\__/\__/   /_/|_|\___/
           Reconfigurable Computing platform
           Copyright (c) 2020, ENSTA Bretagne
           Copyright (c) 2020, EnjoyDigital
```

# Juliet-RC platform
Juliet-RC is a Reconfiurable Computing platform that aims to provide the base infrastruscrure for
FPGA researchs and experiments at ENSTA Bretange.

Juliet-RC is based on Migen/LiteX and provides a SoC skeleton with:
- RISC-V Softcore CPU (VexRiscv (default), PicoRV32 or others)
- Wishbone bus infrastructure + CSR registers.
- LiteDRAM DRAM core with configurable MMAP/DMAs ports.
- Serial control bridge.
- LiteEth Ethernet core with up to 10Gbps MAC/IP/UDP stack + Wishbone control bridge (Etherbone).
- LitePCIe PCIe PHY + configurable DMAs + Wishbone control bridge.
- LiteScope embedded Logic Analyzer.

Examples will be provided to:
- use the Softcore CPU and load custom binary and debug over GDB.
- exercice the Ethernet/PCIe/Serial control bridges from the Host computer.
- add new DRAM user ports.
- add new PCIe user DMAs.
- add new Ethernet UDPs user ports.
- add new peripherals/modules to the SoC and integrate them in the infrastructure.
