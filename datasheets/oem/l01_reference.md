# L01 OEM Baseboard Reference

![](../../.gitbook/assets/l01-reference%20%281%29.png)

The L01 OEM reference board is a reference design suitable for the L01 as well as the W01. It makes it possible to have a single PCB design that can accommodate both of the  OEM modules.

{% hint style="info" %}
If you require a reference board for the L04 or G01, this design is **not** suitable as it does not feature a SIM slot or the double antenna connection. For the L04 or G01 please use the [Universal OEM Baseboard Reference](universal_reference.md)
{% endhint %}

## Features

* Suits both L01 or W01 OEM Modules
* U.FL connector for the L01's LoRa output
* On-board 2.4GHz antenna for WiFi and Bluetooth, with the ability to switch to an external antenna via a U.FL connector
* WS2812B RGB LED
* DC-DC regulator (3.5 - 5.5V) input with low current draw during Deep Sleep
* Reset button

## Layout

The layout of the L01 baseboard reference is available as a PDF File.

{% file src="../../.gitbook/assets/l01-oem-layout.pdf" caption="L01 OEM Layout" %}

![](../../.gitbook/assets/l01-oem-layout-1.png)

## Schematic

The schematic of the L01 baseboard reference is available as a PDF File.

{% file src="../../.gitbook/assets/l01-oem-schematic.pdf" caption="L01 OEM Schematic" %}

## Altium Project and Gerber Files

The Altium Project and Gerber files are also available as a ZIP File.

{% file src="../../.gitbook/assets/l01-oem-baseboard-ref.zip" caption="L01 OEM Altium Project and Gerber Files" %}
