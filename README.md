# Asus Pro P2530UJ EFI Hackintosh MacOs Monterey (WIP)

Running system screenshot:

![Screen Shot 2022-12-30 at 11 37 25 PM](https://user-images.githubusercontent.com/72944953/210122650-7b6df91f-34f8-495d-9224-017c1d9fb6c9.png)

# System details:

| Model            | Asus Pro P2530UJ-XO0104E                                     |
| :--------------- | :----------------------------------------------------------- |
| Processor        | Intel i7-6500U                                               |
| iGPU             | Intel HD Graphics 520                                        |
| dGPU             | NVIDIA GeForce 920m*                                         |
| RAM              | 1x 2133MHz DDR4 8GB                                          |
| WiFi / BT        | Qualcomm Atheros qca9377*                                    |
| Audio            | Conexant CX20751                                             |
| Keyboard         | PC/AT Enhanced PS/2 Keyboard (101/102-Key)                   |
| Touchpad         | ETD0108 Elan                                                 |
| OpenCore Version | 0.8.6                                                        |

* Dedicated GPU not supported.
* Wi-Fi and Bluetooth adapter not supported.

Tips: Use 2x RAM and SSD instead of HDD. It’ll avoid a laggy setup. Buy and install a Wi-Fi & Bluetooth compatible adapter.

Geekbench:

![Screen Shot 2022-12-31 at 8 42 05 PM](https://user-images.githubusercontent.com/72944953/210157688-6e670a64-698a-47d5-ac21-a1eba9a80eb9.png)


# Not working:

| Touchpad*               |
| :---------------------- |
| Wi-Fi & Bluetooth       |
| dGPU                    |
| HDMI                    |

* I'm working to optimize EFI and found that it's possible to active ETD0108 Elan touchpad with ApplePS2SmartTouchPad.kext. It'll probably be working in the next EFI version.

# Not tested:

| SD Slot                 |
| :---------------------- |
| VGA                     |
