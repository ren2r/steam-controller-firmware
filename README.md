# Steam controller hardware
* NXP LPC11U37F 32-bit ARM Cortex-M0(https://www.nxp.com/docs/en/data-sheet/LPC11U3X.pdf)
* Nordic Semiconductor nRF51822 Bluetooth Smart and 2.4GHz proprietary SoC(https://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF51822)
* Invensense MPU-6500 Six-Axis (Gyro + Accelerometer) MEMS MotionTracking device(https://www.invensense.com/products/motion-tracking/6-axis/mpu-6500/)
* Touch panal GlidePoint TM040040 probably with SPI(http://www.cirque.com/glidepoint-circle-trackpads)

# Port bindings

| Port          | Action                  |
| ------------- | -------------           |
| PIO0_17       | A button                |
| PIO0_21       | Steam button led        |
| PIO1_0        | Joystick click          |
| PIO1_2        | Start button            |
| PIO1_3        | Right grip              |
| PIO1_4        | Left bumper             |
| PIO1_9        | X button                |
| PIO1_11       | Y button                |
| PIO1_13       | Right trigger click*    |
| PIO1_14       | Right bumper            |
| PIO1_19       | Steam button            |
| PIO1_20       | Select button           |
| PIO1_21       | Right touch panel click |
| PIO1_22       | B button                |
| PIO1_25       | Left grip               |
| PIO1_26       | Left touch panel click  |
| PIO1_27       | Left trigger click      |

*Right trigger click also connected to PIO0_1 for activation IAP 

# Useful links
Steam Controller Teardown(https://ru.ifixit.com/Teardown/Steam+Controller+Teardown/52578)
