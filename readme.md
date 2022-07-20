# esp32_12chan_lowside_pwm_pcb

Open Hardware PCB designed to drive 12 lowside pwm channels.

It's designed to work with WLED firmware and can drive 4 RGB LED strips.

You can however use it for whatever you want.
Free-wheeling diodes where added, in case someone wants to use it to drive bigger inductive loads.

[img_front](renderings/pcb_esp32_wled_pwm_multichannel_front.jpg)

## Power

### Input

Power by USB for easy flashing.

Or power via screw-terminal: DC from 4V up to 28V.

### Output

The four screw terminals each group VDD as well as 4 gpio controlled pwm-channels to GND.

- terminal 1: VDD, gpio16, gpio17, gpio18
- terminal 2: VDD, gpio19, gpio21, gpio22
- terminal 3: VDD, gpio23, gpio25, gpio26
- terminal 4: VDD, gpio27, gpio32, gpio33

