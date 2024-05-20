# NES Controller Port

Harry Boyd - hboyd255@gmail.com - 04/04/2024

This is a KiCad library for the NES Controller port. The part can be found on
[zedlabz.com](https://www.zedlabz.com/products/controller-connector-port-for-nintendo-nes-console-7-pin-90-degree-replacement-2-pack-black-zedlabz?_pos=8&_sid=b3d25e834&_ss=r).

## Setup

To get the library working, you need to add path of this repository to the KiCad
library search path. This can be done by going to
`Preferences -> Configure Paths` and adding the path with the name
`NES_Controller_Port`.

Then you just need to add `NES_Controller_Port.kicad_sym` to your symbol
libraries table with `Preferences -> Manage Symbol Libraries`.

## Dimensions

The dimensions are based on this image, that I found on
[raphnet-tech.com](https://www.raphnet-tech.com/products/nes_controller_connector/index.php).

![NES Port Technical Drawing](https://www.raphnet-tech.com/products/nes_controller_connector/nes_connector_ra_dims.png)

## Pinout

This diagram from
[raspberryfield.life](https://www.raspberryfield.life/2018/09/01/nespi-project-part-4-the-nes-controller-protocol/)
shows how the terminals are connected.

![NES Port Wiring Diagram](https://www.raspberryfield.life/wp-content/uploads/2018/08/NESPi_part4_web1.jpg)
