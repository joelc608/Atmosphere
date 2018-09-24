# Fusée

Fusée is a custom bootloader needed to start Atmosphère and replaces Nintendo's Package1loader/bootloader. It currently utilizes the Tegra X1 RCM Vulnerability in order to function.

Fusée is split into two separate parts, fusée-primary and fusée-secondary. This is due to the RCM Vulnerability only allowing payloads of a limited filesize to be sent to the device.

## Fusée-Primary

Fusée-primary is the payload file sent to the Switch from an external device. Once sent, fusée-primary makes initial preparations before loading
