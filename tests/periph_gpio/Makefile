include ../Makefile.tests_common

FEATURES_REQUIRED = periph_gpio
FEATURES_REQUIRED = periph_gpio_irq

USEMODULE += shell
USEMODULE += benchmark

include $(RIOTBASE)/Makefile.include

bench:
	tests/02-bench.py
