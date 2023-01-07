# Asus Pro P2530UJ EFI Hackintosh MacOs Monterey

Running system screenshot:

![Screen Shot 2022-12-30 at 11 37 25 PM](https://user-images.githubusercontent.com/72944953/210122650-7b6df91f-34f8-495d-9224-017c1d9fb6c9.png)

I don't know if someone will ever see this Hackintosh rep. since Asus Pro P2530UJ isn't a mainstream laptop, this is my first Hackintosh and i hope it can help someone with this model, tho.

# System details:

| Model            | Asus Pro P2530UJ-XO0104E                                     |
| :--------------- | :----------------------------------------------------------- |
| Processor        | Intel i7-6500U                                               |
| iGPU             | Intel HD Graphics 520                                        |
| dGPU             | NVIDIA GeForce 920m*                                         |
| RAM              | 1x 2133MHz DDR4 8GB                                          |
| WiFi / BT        | Qualcomm Atheros qca9377*                                    |
| Audio            | Conexant CX20751 (alcid=3)                                   |
| Keyboard         | PC/AT Enhanced PS/2 Keyboard (101/102-Key)                   |
| Touchpad         | ETD0108 Elan                                                 |
| OpenCore Version | 0.8.8                                                        |

* Dedicated GPU not supported.
* Wi-Fi and Bluetooth adapter not supported.

Tips: Use 2x RAM and SSD instead of HDD. It’ll avoid a laggy setup. Buy and install a Wi-Fi & Bluetooth compatible adapter. If you need Wi-Fi but can't afford, install HoRNDIS Android USB Tethering Driver for Mac Os X.

Geekbench:

![Screen Shot 2023-01-06 at 1 10 30 PM](https://user-images.githubusercontent.com/72944953/211129110-f135d171-80ae-4a9f-90ec-b2848e218d67.png)


# Not working:

| Wi-Fi & Bluetooth       |
| :---------------------- |
| dGPU                    |
| HDMI                    |
| Fn Bright Keys*         |

* It's possible to enable Fn Bright Keys patching DSDT directly or using SSDTs, but i don't want to.


# Not tested:

| SD Slot                 |
| :---------------------- |
| VGA                     |


Everything else is working.

Note: You'll have to create your own Platform Info in order to have Apple services working. For further information, see Fixing IServices section at Dortania's Post Install Guide.
