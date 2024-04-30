# Charybdis - ZMK - Config


|![DSC09695](https://github.com/superxc3/zmk-config-charybdis_nano/assets/79617315/9ba9cfbd-cc29-4678-83e3-f499a401b5f7)|
|:--:|
|For charybdis nano 3x5, please fork this github.|

|![image](https://github.com/superxc3/zmk-config-charybdis_nano/assets/79617315/2c3e647a-d1d5-4919-812e-dedd7e7075d8)|
|:--:|
|You may use nickcoutsos's [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) to edit ZMK keymaps using browser. |

<br>

## Trackball function

|![image](https://github.com/superxc3/zmk-config-charybdis_nano/assets/79617315/e0165ade-d2d7-4b11-ab9d-1bb44d31896d)|
|:--|
| Default mouseclicks and scroll combo |

1. Scroll on Layer 5, to change the default scroll layer, go to this [line](https://github.com/superxc3/zmk-config-charybdis_nano/blob/9bfd03ef721dab9a8e3f21a3535fabae094affd0/config/boards/shields/charybdis/charybdis_right.overlay#L61C1-L61C29)
2. Snipe on Layer 6, to change the default snipe (move slower for precision) layer, go to this [line](https://github.com/superxc3/zmk-config-charybdis_nano/blob/9bfd03ef721dab9a8e3f21a3535fabae094affd0/config/boards/shields/charybdis/charybdis_right.overlay#L62)

<br>

## Side note
1. This is built based on [grassfedreeve](https://github.com/grassfedreeve/Charybdis-ZMK-Config).
2. Tangbonze has configured to fit for the pmw3610 driver, scroll and snipe function.
3. I have reduced unnecessary layer and revised the default scroll and snipe layers. 
