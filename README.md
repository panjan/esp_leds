# ESP Leds Controller

RGB LED strip controller for ESP8266. Go to `http://leds.local` to access the UI.

## Flashing

``` sh
# Install PlatformIO CLI
> brew install platformio # Mac specific

# Install packages
> platformio lib install

# Upload firmware over serial connection
> platformio run -t upload --upload-port <your_serial_port>

# Monitor serial port
> pio device monitor
```

## Over the Air Updates

```
platformio run --target upload
```