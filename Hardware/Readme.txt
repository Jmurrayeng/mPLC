Minimally viable PLC like device based on an RP2040

The board requires a 24VDC power supply and produces a 10V and 5V power supply on the power out connectors
The internal 3.3VDC power supply supply is accessable via the programming/expansion header

There are 11 24VDC inputs (gpio 0 to 10) and 11 open collector outputs (gpio 11-22)
The 4 ADC (gpio 26 to 29) are suitable for 0-10V

The remaining 4 gpio are taken to the programming/expansion header along with serial wire debug


