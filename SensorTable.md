|              |        |               |     |Accelerometer     |                 |                                     |             |Gyroscope         |                 |                          |                    |       |
| ------------ | ------ | ------------- | --- | ---------------- | --------------- | ----------------------------------- | ----------- | ---------------- | --------------- | ------------------------ | ------------------ | ----- |

| Manufacturer | Sensor | F/C Evidence? | DoF | A Max Rate (KHz) | A ADC Data Bits | A Sensitivity (g) (LSB Sensitivity) | A Range (g) | G Max Rate (KHz) | G ADC Data Bits | G Sensitivity (degs/sec) | G Range (degs/sec) | Notes |
| ------------ | ------ | ------------- | --- | ---------------- | --------------- | ----------------------------------- | ----------- | ---------------- | --------------- | ------------------------ | ------------------ | ----- |
|TDK InvenSense (Japan/US) |	MPU6050 |	y	| 6 |	1	| 16	| 6.10352E-05 |	"+-2g to +-16g" |	8	| 16	| 0.007633588	|"+-250degs/sec to +-2000 degs/sec"|	g res quoted as 131LSB per deg per s a res quotes 16384LSB/g|
|TDK InvenSense (Japan/US) | MPU9250	| y	| 9	| 4	| 16	| 6.10352E-05	| "+-2g to +-16g"	| 8	| 16	| 0.007633588	| "+-250degs/sec to +-2000 degs/sec"|	g res quoted as 131LSB per deg per s |
|STMicroelectronics (EU)	| LSM6DSOX	| 	|6	|6.664	| 16	| 0.000061	| "+-2g to +-16g"	| 6.664	| 16	| 0.004375	| "+-125degs/sec to +-2000degs/sec" |	g res quoted as mdps/LSB a res quoted as 0.061mg/LSB |
|STMicroelectronics (EU)	| LSM6DSO32	| 	| 6	| 6.664	| 16	| 0.000122	| "+-4g to +-32g" |	6.664	| 16	| 0.004375	| "+-125degs/sec to +-2000degs/sec"	| g res quoted as 4.375mdps/LSB a res quoted as 0.122mg/LSB |
|STMicroelectronics (EU)	| LSM6DS3TR-C | |		| 6	| 6.664	| 16	| 0.000061	| "+-2g to +-16g"	| 6.664	| 16	| 0.004375	| "+-125degs/sec to +-2000degs/sec" |	g res quoted as 4.375mdps/LSB a res quoted as 0.061mg/LSB |
|STMicroelectronics (EU)	| LSM9DS1 (SLOW!) |	|	| 9	| 0.952	| 16	| 0.000061	| "+-2g to +-16g"	| 0.952	| 16	| 0.00875	| "+-245degs/sec to +-2000degs/sec"	| LOW ODR - NOT SUITED TO DRONE -g res quoted as 8.75mdps/LSB a res quoted as 0.061mg/LSB |



