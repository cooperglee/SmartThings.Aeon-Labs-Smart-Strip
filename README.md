# SmartThings Device Type and SmartApp for Aeotec by Aeon Labs’ Smart Strip
===========

SmartThings Device Type and SmartApp for Aeotec by Aeon Labs’ Smart Strip

http://aeotec.com/z-wave-power-strip

## Installation

1. Create new device type using Aeon-Labs-Smart-Strip.device-type.groovy.

2. Create new SmartApp using http://community.smartthings.com/t/zwave-power-strip-from-aeon/947/108.

3. Create new device type using based on http://thinkmakelab.com/2014/06/11/how-to-create-a-virtual-switch-in-smartthings/.

4. Create 4 new virtual switch devices using the device type in step 3.

5. Change the device type for your power strip to the device type created in step 1.

6. Add a new SmartApp instance using the SmartApp created in step 2.

7. Configure the SmartApp to point to the 4 virtual switches and power strip.


Device Type is based on http://community.smartthings.com/t/zwave-power-strip-from-aeon/947/90.
SmartApp is based on http://community.smartthings.com/t/zwave-power-strip-from-aeon/947/108.