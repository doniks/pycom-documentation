# GPy

![](../../.gitbook/assets/gpy-1.png)

**Store**: [Buy Here](http://www.pycom.io/gpy)

**Getting Started:** [Click Here](../../gettingstarted/connection/gpy.md)

## Pinout

The pinout of the GPy is available as a PDF File

{% file src="../../.gitbook/assets/gpy-pinout.pdf" caption="GPy Pinout" %}

![](../../.gitbook/assets/gpy-pinout.png)

{% hint style="info" %}
Please note that the PIN assignments for UART1 \(TX1/RX1\), SPI \(CLK, MOSI, MISO\) and I2C \(SDA, SCL\) are defaults and can be changed via software.
{% endhint %}

## Datasheet

The datasheet of the GPy is available as a PDF File.

{% file src="../../.gitbook/assets/gpy-specsheet.pdf" caption="GPy Datasheet" %}

The drawing of the LTE-M antenna is available as a PDF File.

{% file src="../../.gitbook/assets/lte-m-antenna-drawing.pdf" caption="LTE-M Antenna Drawing" %}

## Notes

### WiFi

By default, upon booting up the GPy will create a WiFi access point with the SSID `gpy-wlan-XXXX`, where `XXXX` is a random 4-digit number, and the password `www.pycom.io`.

The RF switch that selects between the on-board and external antenna is connected to `P12`, so for this reason using `P12` should be avoided unless WiFi is disabled in your application.

### Power

The `Vin` pin on the GPy can be supplied with a voltage ranging from `3.5v` to `5.5v`. The `3.3v` pin on the other hand is output **only**, and must not be used to feed power into the GPy, otherwise the on-board regulator will be damaged.

### AT Commands

The AT commands for the Sequans Monarch modem on the GPy are available in a PDF file.

{% file src="../../.gitbook/assets/monarch\_4g-ez\_lr5110\_atcommands\_referencemanual\_rev3\_noconfidential-1.pdf" caption="AT Commands for Sequans" %}

## Tutorials

Tutorials on the GPy module can be found in the [examples](../../tutorials/introduction.md) section of this documentation. The following tutorials might be of interest for those using the GPy:

* [WiFi connection](../../tutorials/all/wlan.md)
* [LTE CAT-M1](../../tutorials/lte/cat-m1.md)
* [NB-IoT](../../tutorials/lte/nb-iot.md)
* [BLE](../../tutorials/all/ble.md)
