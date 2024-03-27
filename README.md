# Achtung
Dies ist ein Fork der VCNL 4200 I2C Arduino Control Library. In der originalen Library ist ein Bug in der Datei "CRC_VCNL4200.cpp" bzw. ".h". Die Funktion "CRC_VCNL4200::write16_LowHigh" hat im originalen einen Rückgabewert als uint16_t gibt aber nie einen Wert zurück. Dies führt zu einem Absturz.

# CRC_VCNL4200
VCNL 4200 I2C Control Library

This library is for control of the Vishay "High Sensitivity Long Distance Proximity and Ambient Light Sensor With I²C Interface".  Details can be found here: https://www.vishay.com/optical-sensors/list/product-84430/

A 5V compliant board that works with standard Arduino can be found here: https://oshpark.com/shared_projects/C7N990kt

