|              |        |               |     |Accelerometer     |                 |                                     |             |Gyroscope         |                 |                          |                    |       |
| ------------ | ------ | ------------- | --- | ---------------- | --------------- | ----------------------------------- | ----------- | ---------------- | --------------- | ------------------------ | ------------------ | ----- |

| Manufacturer              | Sensor        | F/C Evidence? | DoF | A Max Rate (KHz) | A ADC Data Bits | A Sensitivity (g) (LSB Sens) | A Range (g)   | G Max Rate (KHz) | G ADC Data Bits | G Sensitivity (degs/sec) | G Range (degs/sec)    | Notes |
| ------------------------- | ------------- | ------------- | --- | ---------------- | --------------- | ---------------------------- | ------------- | ---------------- | --------------- | ------------------------ | --------------------- | ----- |
| TDK InvenSense (Japan/US) |	MPU6050       |	y           	| 6   |	1	               | 16	             | 6.10352E-05                  |	+-2g to +-16g |	8	               | 16	             | 0.007633588	            | +-250d/s to +-2000d/s |	g res quoted as 131LSB per deg per s a res quotes 16384LSB/g|
| TDK InvenSense (Japan/US) | MPU9250	      | y	            | 9	  | 4	               | 16	             | 6.10352E-05	                | +-2g to +-16g	| 8	               | 16	             | 0.007633588	            | +-250d/s to +-2000d/s |	g res quoted as 131LSB per deg per s |
| STMicroelectronics (EU)	  | LSM6DSOX	    | 	            | 6	  | 6.664	           | 16	             | 0.000061	                    | +-2g to +-16g	| 6.664	           | 16	             | 0.004375	                | +-125d/s to +-2000d/s |	g res quoted as mdps/LSB a res quoted as 0.061mg/LSB |
| STMicroelectronics (EU)	  | LSM6DSO32	    | 	            | 6	  | 6.664	           | 16	             | 0.000122	                    | +-4g to +-32g |	6.664	           | 16	             | 0.004375	                | +-125d/s to +-2000d/s	| g res quoted as 4.375mdps/LSB a res quoted as 0.122mg/LSB |
| STMicroelectronics (EU)	  | LSM6DS3TR-C   |               | 6	  | 6.664	           | 16	             | 0.000061	                    | +-2g to +-16g	| 6.664	           | 16	             | 0.004375	                | +-125d/s to +-2000d/s |	g res quoted as 4.375mdps/LSB a res quoted as 0.061mg/LSB |
| STMicroelectronics (EU)	  | LSM9DS1 (SLOW)|	            	| 9	  | 0.952	           | 16	             | 0.000061	                    | +-2g to +-16g	| 0.952	           | 16	             | 0.00875	                | +-245d/s to +-2000d/s	| LOW ODR - NOT SUITED TO DRONE -g res quoted as 8.75mdps/LSB a res quoted as 0.061mg/LSB |
| Bosch Sensortec (Germany)	| BNO055 (IMU)	|               | 9	  | 1	               | 14?	           | 0.001	                      | +-2g to +-16g	| 0.523	           | 16	             | 0.0625	                  | +-125d/s to +-2000d/s |	IMU - SLOW!: g res quoted as 16 LSB/deg/s, a res quoted as 1LSB/mg HAS MAG4GYRO MODE in FUSION ODG is 100Hz for NDOF fusion |
| Bosch Sensortec (Germany)	| BMIO88	      | y	            | 6	  | 1.6	             | 16	             | 9.15751E-05	                | +-3g to +-24g	| 2	               | 16	             | 0.003814697	            | +-125d/s to +-2000d/s | g res quoted as 262.144LSB/deg/s a res quoted as 10920 LSB/g |
| Bosch Sensortec (Germany)	| BMi270	      | y	            | 6	  | 1.6	             | 16	             | 6.10352E-05	                | +-2g to +-16g	| 6.4	             | 16	             | 0.003814697	            | +-125d/s to +-2000d/s	| g sens quoted as 262.144 LSB/dps a sens quoted as 16384 LSB/g |
| STMicroelectronics (EU)	  | ISM330DHCX	  |               |	6	  | 6.667	           | 16	             | 0.061	                      | +-2g to +-16g	| 6.667	           | 16	             | 4.375	                  | +-125 d/s to +-4000d/s	| a sens quoted as 0.016 mg/LSB g sens mdsp/LSB |
| STMicroelectronics (EU)	  | ISM330BX	    | |										
| STMicroelectronics (EU)	  | ISM330ISTR	  | |										
| TDK InvenSense (Japan/US)	| ICM20948	    |               |	9	  | 4.5	             | 16	             | 6.10352E-05	                | +-2g to +-16g	| 9	               | 16	             | 0.007633588	            | +-250d/s to +-2000d/s	| gyro quotes 131 LSB/(dps) acc quotes 16384 LSB/g |
| TDK InvenSense (Japan/US)	| ICM-42688-P   |	y	            | 6	  | 32	             | 18	             | 6.10352E-05	                | +-2g to +-16g	| 32	             | 19	             | 0.000476826	            | +-15.6d/s to +-2000d/s	| best drone gyro of range g sens quoted as 2097.2 LSB per deg per sec ass quotes 16384 LSB/g |
| TDK InvenSense (Japan/US)	| ICM-42686-P	  |               |		  | 32? |								
| TDK InvenSense (Japan/US)	| ICM-40607		  |               |	    | 8?	|							
| TDK InvenSense (Japan/US)	| ICM-42605		  |               |	    | 8?	|							
| TDK InvenSense (Japan/US)	| IAM20380	    |               |	3	  | 8	|			
| TDK InvenSense (Japan/US)	| ICM-42602???	| y	            | need ds	|								
| TDK InvenSense (Japan/US)	| ICM-20649???	| y	            | need ds	|								
| TDK InvenSense (Japan/US)	| ICM-42670-P???| y	            | need ds	|								
| TDK InvenSense (Japan/US)	| ICM-45686???	| y	            | need ds	|								BALANCED gyro? |
| HBK Microstrain	          | 3DM-CV7-AR	  |								|		PX4 |
| HBK Microstrain	          | 3DM-CV7-AHRS	|								|		PX4 |
| Movella	MTi600            | Xsens series	|								|		Not usable for flight, low refresh |
| Analog Devices (US)       |	ADXRS646	    |	              | 1		|							*** 1 axis gyro, voltage proportional to rotation rate |
| Analog Devices (US)	      | ADXL345		    |               | 3	  | 3.2	|							Accelerometer only |
| Analog Devices (US)	      | ADXRS450	    |	              | 3?	|								80Hz update? Gyro only? |
| muRata (Japan)	          | SCHA63T-K03		|               |     | 8.9	|							£400 specifies UAV use |




