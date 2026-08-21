---
title: "Skibidi USB Mux"
github: "https://github.com/tobycm/skibidi-usb-mux"
description: "A simple USB mux with 2 upstream USB C ports and 3 downstream USB A ports and 1 downstream USB C port."
created_at: "2026-08-20"
---

# August 19: Compiled a mental part list and started on schematic

Ended up with using the onsemi FSUSB42MUX for switching between 2 data pairs and using my favourite USB hub IC, the WCH CH334P, to expand to more ports.

![sch1](assets/sch1.png)

**Total time spent: 1h**

# August 20: Completed the schematic and PCB layout and routing

The truth table for the state of the mux:

![mux truth table](assets/mux_tt.png)

i realizd a latching switch is the best for this, so i picked the [G-Switch PS-5850A-6PL](https://www.lcsc.com/product-detail/C963201.html)

Final PCB look:

![pcb](assets/pcb.png)

**Total time spent: 1h**

# August 20 night: Decorated PCB

Shoutout to everyone who agreed to be on my PCB 🔥🔥🔥

![pcb2](assets/pcb2.png)
![pcb3](assets/pcb3.png)


**Total time spent: 2h**