# Aeon-HEM-Gen5
Updating Aeon HEM Gen5 Hubitat Driver


1 - got it to report more data in the Maker API
2 - cleaned up some errors
3 - going to see what else it needs - getting things like this
<code>
dev:3902020-01-19 16:34:54.303 debugUnhandled: Crc16Encap(checksum:65535, command:13, commandClass:96, data:[2, 0, 50, 2, 33, 100, 0, 1, 128, 58, 0, 59, 0, 1, 128, 27])
dev:3902020-01-19 16:34:54.029 debugUnhandled: Crc16Encap(checksum:65535, command:13, commandClass:96, data:[1, 0, 50, 2, 33, 100, 0, 1, 38, 120, 0, 59, 0, 1, 38, 81])
dev:3862020-01-19 16:34:53.834 infoPower 2 power is 88.802 W
dev:3902020-01-19 16:34:53.814 debugUnhandled: Crc16Encap(checksum:65535, command:13, commandClass:96, data:[1, 0, 50, 2, 161, 108, 0, 0, 76, 24, 0, 60, 0, 0, 73, 102])
dev:3862020-01-19 16:34:53.525 infoPower 2 energyDuration is 14.09 Days 
dev:3902020-01-19 16:34:53.244 debugUnhandled: Crc16Encap(checksum:65535, command:13, commandClass:96, data:[2, 0, 50, 2, 161, 100, 0, 1, 225, 56, 0, 60, 0, 1, 225, 239])
dev:3862020-01-19 16:34:53.226 infoPower 2 current is 0.783 A
dev:3902020-01-19 16:34:52.937 debugUnhandled: Crc16Encap(checksum:65535, command:13, commandClass:96, data:[1, 0, 50, 2, 161, 100, 0, 1, 225, 56, 0, 60, 0, 1, 225, 239])
dev:3902020-01-19 16:34:52.840 debugUnhandled: Crc16Encap(checksum:65535, command:2, commandClass:50, data:[33, 100, 0, 2, 166, 178, 0, 16, 0, 2, 166, 108])
dev:3902020-01-19 16:34:52.740 debugUnhandled: Crc16Encap(checksum:65535, command:2, commandClass:50, data:[33, 116, 0, 61, 51, 36, 0, 14, 0, 61, 59, 196])
dev:3902020-01-19 16:34:52.648 debugUnhandled: Crc16Encap(checksum:65535, command:2, commandClass:50, data:[161, 108, 0, 0, 131, 249, 0, 17, 0, 0, 132, 16])
dev:3902020-01-19 16:34:52.541 debugUnhandled: Crc16Encap(checksum:65535, command:2, commandClass:50, data:[161, 100, 0, 1, 225, 56, 0, 18, 0, 1, 225, 29])
</code>
