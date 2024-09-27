# logisim-evolution-mod
 
This repository contains an unofficial modification of Logisim Evolution. To view the original code, please refer to the official repository at https://github.com/logisim-evolution/logisim-evolution.

In this modified version (based on version 3.9.0), the following changes have been made:

- Only the AlteraDownload.java file has been modified.
  - If both SOF and POF files are available for FPGA download, you can now choose between them.
  - Unused pins are now treated as inputs.

These changes have been verified using Intel Quartus Prime Lite 18.1 (Windows) with MAX10 devices.