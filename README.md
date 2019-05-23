# piplaypen
## Unicorn 
```python 
unicornhathd.clear()
unicornhathd.show()
unicornhathd.off()
unicornhathd.rotation(r)
unicornhathd.get_rotation()
unicornhathd.brightness(b)
unicornhathd.set_pixel(x, y, r, g, b)
unicornhathd.set_pixel_hsv(x, y, h, s=1.0, v=1.0)
```
## LED Shim
```python 
ledshim.clear()
ledshim.show()
ledshim.set_pixel(x, r, g, b, brightness=1.0)
ledshim.set_multiple_pixels(indexes, from_colour, to_colour=None)
ledshim.set_all(r, g, b, brightness=1.0)
ledshim.set_brightness(brightness)
ledshim.set_clear_on_exit(value=True)
ledshim.set_gamma(gamma_table)?
# ledshim.setup()???  
# ledshim.get_shape()  
# Matrix.height 
# Matrix.width
``` 
## Touch Hat
```python 
touchphat.all_off()
touchphat.all_on()
touchphat.led_off(pad)
touchphat.led_on(pad)
touchphat.on_release(pad, handler=None)
touchphat.on_touch(pad, handler=None)
```
