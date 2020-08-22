# sigrok_emmc_decoder
Created from sigrok_sdcard_sd decoder, a sample emmc decoder for sigrok
## eMMC Protocol
Currently, the decoder is created based on eMMC protocol Ver 5.0 without HS400 or DDR support, nor does it have data decoding. It supports command decoding.
CMD is defined using eMMC protocol chapter 6.10.4 and 6.12
