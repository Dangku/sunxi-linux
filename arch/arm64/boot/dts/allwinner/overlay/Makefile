# SPDX-License-Identifier: GPL-2.0
dtbo-$(CONFIG_ARCH_SUNXI) += \
	sun55i-t527-i2c1.dtbo \
	sun55i-t527-i2c4.dtbo \
	sun55i-t527-i2c5.dtbo \
	sun55i-t527-i2c5-eeprom.dtbo \
	sun55i-t527-i2c5-rtc.dtbo \
	sun55i-t527-uart2.dtbo \
	sun55i-t527-uart3.dtbo \
	sun55i-t527-uart4.dtbo \
	sun55i-t527-uart5.dtbo \
	sun55i-t527-uart6.dtbo \
	sun55i-t527-uart7.dtbo \
	sun55i-t527-pwm0.dtbo \
	sun55i-t527-pwm1.dtbo \
	sun55i-t527-pwm2.dtbo \
	sun55i-t527-pwm3.dtbo \
	sun55i-t527-pwm4.dtbo \
	sun55i-t527-pwm5.dtbo \
	sun55i-t527-pwm6.dtbo \
	sun55i-t527-pwm7.dtbo \
	sun55i-t527-pwm8.dtbo \
	sun55i-t527-pwm9.dtbo \
	sun55i-t527-pwm10.dtbo \
	sun55i-t527-pwm11.dtbo \
	sun55i-t527-pwm12.dtbo \
	sun55i-t527-pwm13.dtbo \
	sun55i-t527-spi1-spidev.dtbo \
	sun55i-t527-spi1-flash.dtbo \
	sun55i-t527-spi1-waveshare-tft24.dtbo \
	sun55i-t527-spi1-waveshare-tft35c.dtbo \
	sun55i-t527-spi1-waveshare-st7789v.dtbo \
	sun55i-t527-spi2-spidev.dtbo \
	sun55i-t527-i2s0-mic-mems.dtbo \
	sun55i-t527-i2s0-nxez-pcm512x.dtbo \
	sun55i-t527-i2s0-waveshare-wm8960.dtbo \
	sun55i-t527-edp-aml133x30.dtbo

scr-$(CONFIG_ARCH_SUNXI) += \
	sun55i-t527-fixup.scr

dtbotxt-$(CONFIG_ARCH_SUNXI) += \
	README.sun55i-t527-overlays

targets += $(dtbo-y) $(scr-y) $(dtbotxt-y)

always-y       := $(dtbo-y) $(scr-y) $(dtbotxt-y)
clean-files    := *.dtbo *.scr
