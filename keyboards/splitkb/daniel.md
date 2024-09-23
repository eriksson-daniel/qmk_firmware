# Hilsen Daniel
## Konvertere JSON keymap (fra QMK Configurator) til C
```Windows
qmk json2c -o /c/Users/Daniel/qmk_firmware/keyboards/splitkb/kyria/keymaps/daniel/keymap.c /c/Users/Daniel/qmk_firmware/keyboards/splitkb/kyria/keymaps/daniel/daniel.json
```
```Linux
qmk json2c -o /home/daniel/repos/qmk_firmware/keyboards/splitkb/kyria/keymaps/daniel/keymap.c /home/daniel/repos/qmk_firmware/keyboards/splitkb/kyria/keymaps/daniel/daniel.json
```

## Kompilere
```
qmk compile -e CONVERT_TO=liatris -kb splitkb/kyria/rev3 -km daniel
```
