# door_sign
This repo will be used for files relating to the doorsign for Digitala Verksta'n

## About
We will probably have a small display mounted on the door connected to a Raspberry Pi or something like it to display upcoming events etc.

## Dependencies:
The cat clone **bat** is used for presenting the .md with syntax coloring.

## QR codes
Are generated with **qrencode**
```bash
qrencode -t ansiutf8 < file_with_link
```
