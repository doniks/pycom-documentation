# Expansion Board 2.0

![](../../.gitbook/assets/expansion2.png)

## Pinout

The pinout of the Expansion Board is available as a PDF File

{% file src="../../.gitbook/assets/expansion2-pinout.pdf" caption="Expansion Board 2 Pinout" %}

![](../../.gitbook/assets/expansion2-pinout-1.png)

{% hint style="danger" %}
Be gentle when plugging and unplugging from the USB connector. Whilst the USB connector is soldered and is relatively strong, if it breaks off it can be very difficult to fix.
{% endhint %}

## Battery Charger

The Expansion Board features a single cell Li-Ion/Li-Po charger. When the board is being powered via the micro USB connector, the Expansion Board will charge the battery \(if connected\). When the `CHG` jumper is present, the battery will be charged at `450mA`. If this value is too high for your application, removing the jumper lowers the charge current to `100mA`.

## Specsheets

The specsheet of the Expansion Board is available as a PDF File.

{% file src="../../.gitbook/assets/expansion2-specsheet.pdf" caption="Expansion Board 2 Datasheet" %}
