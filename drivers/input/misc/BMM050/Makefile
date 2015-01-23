#
# Makefile for Bosch sensor driver.
#
obj-$(CONFIG_SENSORS_BMM050)    += bmm050_driver.o bmm050.o
EXTRA_CFLAGS += -DBMM_USE_BASIC_I2C_FUNC -DCONFIG_BMM_USE_PLATFORM_DATA
