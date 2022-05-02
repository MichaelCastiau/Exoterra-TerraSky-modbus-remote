# Exoterra Terrasky IR modbus enabled remote

These are the hardware schematics for a STM32 powered 38kHz IR remote that can 'learn' and then send out specfic signals for day, night and twilight lighting effects for the Exo Terrasky light. It makes use of the NEC protocol to learn and send commands.

The purpose is to automate an ExoTerra Terrasky using IR, since the default remote control doesn't have any timers.

RS-485 Modbus RTU can be used to send commands to change the lights, using a Modbus enabled PLC.

**The schematics are drawn using KiCad**