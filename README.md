NXT-Robots
==========
A client-server script for controlling NXT based robots.

This script assumes you have configure the NXT in the car design from the LEGO NXT manual.

Components
==========

* `Docs/` - Directory containing documentation and promotional materials.
* `helpers/` - Various helper scripts used to quickly setup NXT demos.
* `daemon` - Daemon script object. This script listens for commands from a FIFO pipe and relays them to the appropriate NXT object via Bluetooth.
* `keyboard` - Stand-alone keyboard control script for a single NXT robot. Use this to test basic NXT functionality via keyboard.
* `xbox` - Xbox joystrick contoller used to relay commands from an Xbox joypad into a FIFO pipe suitable for reading by `daemon`
