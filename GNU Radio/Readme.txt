### GNU Radio Flowchart Overview
- The gnuradio_flowchart.grc file contains the complete GNU Radio flowchart for the implemented QPSK transceiver.
- The flowchart allows the transmission of files or live voice by enabling/disabling the appropriate blocks.

---
### Simulation Setup
1. To simulate a transmission, connect a channel model between the virtual sink and the virtual source in the flowchart.
2. Disable the rational resampler and bladeRF blocks for this simulation setup.

---
### Transmitter and Receiver Configuration
- The same flowchart can be used on two separate computers for transmission and reception:
  1. On the transmitter, disable all receiver blocks.
  2. On the receiver, disable all transmitter blocks.
