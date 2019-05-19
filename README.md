# Rafael Micro R836 reverse engineering

Trying to reverse engineer the Rafael Micro R836

# I2C Address (7bit)

Depends on pin 15:

- 0x3A (0111010) PIN 15 floating
- 0x1A (0011010) PIN 15 connected to GND

# I2C Address (8bit)

PIN 15 floating:

- 0x74 (01110100): Write Mode
- 0x75 (01110101): Read Mode

PIN 15 connected to GND:

- 0x34 (00110100): Write Mode
- 0x35 (00110101): Read Mode

## Devices

- [LinQ DH1692](LinQ-dh1692/)

