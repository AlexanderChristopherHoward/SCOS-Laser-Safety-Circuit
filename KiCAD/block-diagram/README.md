# SCOS Laser Safety PCB

## Rev 1 ECOs

* Reconnect VCC to 555 on schematic (<em>inconsistent with PCB!</em>)
* need input pull-ups on OVERRIDE, INTERLOCK, KEY_SW
  <br>on prototype, use 470 ohms on pins 1,5,6 of J1
  <br>(or fix on main board so logic driven)
  <br><em>The LEDs complicate this, perhaps LEDs should go to +5V instead?
* MOSFETs Q3, Q4 pinout is wrong :( :(
  <br> solder upside-down on prototype
  


