#
# Makefile for industrial I/O gyroscope sensor drivers
#

# When adding new entries keep the list in alphabetical order
obj-$(CONFIG_ADIS16080) += adis16080.o
obj-$(CONFIG_ADIS16130) += adis16130.o
obj-$(CONFIG_ADIS16136) += adis16136.o
obj-$(CONFIG_ADIS16260) += adis16260.o
obj-$(CONFIG_ADXRS450) += adxrs450.o
obj-$(CONFIG_BMG160) += bmg160.o

obj-$(CONFIG_HID_SENSOR_GYRO_3D) += hid-sensor-gyro-3d.o

itg3200-y               := itg3200_core.o
itg3200-$(CONFIG_IIO_BUFFER) += itg3200_buffer.o
obj-$(CONFIG_ITG3200)   += itg3200.o

obj-$(CONFIG_IIO_SSP_SENSORS_COMMONS) += ssp_gyro_sensor.o

obj-$(CONFIG_IIO_ST_GYRO_3AXIS) += st_gyro.o
st_gyro-y := st_gyro_core.o
st_gyro-$(CONFIG_IIO_BUFFER) += st_gyro_buffer.o

obj-$(CONFIG_IIO_ST_GYRO_I2C_3AXIS) += st_gyro_i2c.o
obj-$(CONFIG_IIO_ST_GYRO_SPI_3AXIS) += st_gyro_spi.o
