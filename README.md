# zmk-config-s60

Keymap config for S60 Blue Edition


## Instruction:
1. Fork this repo
2. Use https://nickcoutsos.github.io/keymap-editor/ as keymap-editor to edit the keymap you prefer (this is not a real-time keymap editor). Remember to give keymap-editor the permission to acess your fork of this repo.
3. Press 'Commit Changes' on keymap-editor page after you are done. Don't forget to set 'BT_CLR' cause you may have to use it when you have connection issue. And it would be better to set a key as reset cause it can help to resume connection when disconnecting.
4. Go to your own fork of this repo, check Actions page. There is a new workflow generating zmk firmware 'zmk.uf2', save it to your PC folder.
5. Press the reset button on the back of PCB twice to put it into bootloader mode(or bootloader soft key). There will be a device popped out. Drag the zmk firmware you generated into the root folder.
6. The device will be refreshed and showed as 'S60'. All done!

## Credit:

ZMK is awesome!
Read the zmk doc here https://zmk.dev/

And thanks to @nickcoutsos for this amazing keymap editor
https://github.com/nickcoutsos/keymap-editor
