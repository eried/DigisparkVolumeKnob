# DigisparkVolumeKnob
Simple USB volume knob using https://s.click.aliexpress.com/e/_dVwsVW7 and a rotary encoder. 

volume_knob.stl and volume_knob_holder.stl are designed around [this module](https://www.aliexpress.com/item/32718891419.html?spm=a2g0o.productlist.0.0.1af8527fZmlRAM&algo_pvid=8eecaf54-b2a6-44fd-a7a7-bcc0136677e5&algo_expid=8eecaf54-b2a6-44fd-a7a7-bcc0136677e5-6&btsid=0bb0623a16009536326803316ed213&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_). The holder is designed to mount the encoder on a 12 mm width material thru a 16 mm hole.

## Wiring

1) Remove the led connected to pin 2 on the digispark
2) Connect GND to the encoder

Follow, but connect RED and BLUE to 0 and 2 pins, and the PINK wire to pin 1 on the digispark:
![](https://github.com/Bluebie/volume_knob/blob/master/media/wiring.png)
