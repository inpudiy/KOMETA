## 1. Tool preparation

For soldering the KOMETA you will need: a soldering iron, solder, flux, side cutters, and tweezers.

![tools](image/build/tools.jpg)

## 2. Component preparation

For soldering you will need: 2 PCBs, 42 PG1350 hot-swap sockets, 42 1N4148WS diodes, 2 TS342A2P and MSK12C02 switches, any Pro Micro–compatible development board based on the nRF52840 (for example, nice!nano or Super Mini nRF52840), as well as a 301230-sized lithium battery.

![set](image/build/set.jpg)

## 3. Soldering the diodes

The first step is to tin one pad of each diode footprint with a small amount of solder.

![tinnig](image/build/tinning_pads.jpg)

Next, align the stripe on the diode with the stripe on the PCB, which is located closer to the square pad.

![diode_line](image/build/diode_line.jpg)
![pcb_line](image/build/line_on_pcb.jpg)

After that, use the soldering iron to reheat the tinned pad and place the diode in position.

![rehat](image/build/reheat.jpg)

Once all the diodes are soldered on one side, solder the second contact of each diode.

![diode](image/build/soldered_diodes.jpg)

## 4. Soldering the key sockets

Simply place all the hot-swap sockets into their footprints and apply solder on both sides.

![hotswap](image/build/hotswap_soldering.jpg)

## 5. Soldering the Reset Button and Switch

Place the buttons into their footprints and apply flux with solder to the contacts.

![buttons](image/build/soldering_buttons.jpg)

## 6. Installing the controller sockets

First, take rows of machine pin sockets and, using side cutters, extract 48 sockets. Simply snip the side and remove the excess plastic.

![sockets_and_side_cutters](image/build/sockets_and_side_cutters.jpg)
![socket_trimming](image/build/socket_trimming.jpg)
![one_socket](image/build/one_socket.jpg)
![many_sockets](image/build/many_sockets.jpg)

The second step is to place them, with the connector facing upward, on the bottom side of the PCB where all the components are located. You can use heat-resistant tape (DO NOT USE REGULAR TAPE, IT WILL DAMAGE THE PCB) to hold them in place during soldering.

![installing_sockets](image/build/installing_sockets.jpg)

Flip the PCB to the top side and apply flux with solder.

Cut the ends of the pins with side cutters.

> [!WARNING]
> Be careful and use eye protection (PLEASE BE EXTRA CAREFUL, AS THE CUT PIECES CAN EASILY FLY INTO YOUR EYE OR YOUR MONITOR SCREEN).

![cutting_racks](image/build/cutting_racks.jpg)

## 7. Soldering the controller

Place the controller on top of the sockets so that the top pins near the connector are not connected to the sockets.
Insert a wire into each contact and cut it with side cutters.

![wire_cutting](image/build/wire_cutting.jpg)

Once the wires are cut, apply flux and solder to all the contacts.

![soldering_controller](image/build/soldering_controller.jpg)

Be careful and make sure that the solder does not flow underneath the controller.

## 8. Installing the battery

Solder the red wire to the + and the black wire to the – on the top side of the PCB, and place the battery in the area near the controller.

![solder_battery](image/build/solder_battery.jpg)

## 9. Flashing

After installing the controller on the board, connect the keyboard to your computer with a USB cable.

Download the archive named **firmware** from this repository: [https://github.com/inpudiy/kometa-zmk/releases](https://github.com/inpudiy/kometa-zmk/releases)

![firmware](image/build/fiwmare.png)

Unpack the archive — inside, you should find two files: one for the left half and one for the right half.

![unzip](image/build/unzip.png)

After extracting the files, press the button on the keyboard located next to the power switch. A new drive should appear in your file explorer.

![button](image/build/soldering_buttons.jpg)

If it doesn’t appear, make sure the controller is functioning (check if the LEDs blink when powered on) and that your cable supports data transfer.

Drag and drop the appropriate file onto the new drive for your half of the keyboard, then repeat the same process for the other half.

If you run into difficulties, please consult the official [troubleshooting](https://zmk.dev/docs/troubleshooting) guide.
