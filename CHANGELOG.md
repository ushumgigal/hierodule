# Change Log {#ChangeLog}
All notable changes to this project will be documented in this file.
 
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.6.2] - 2024-07-27

### Fixed

- Timer Module, preprocessor toggling for timer IRQs, in case they're reserved as timebase for HAL.

## [1.6.1] - 2024-07-26

### Fixed

- USB Module, preprocessor check for the usb device cdc header.

## [1.6.0] - 2024-07-26

### Added

- USB module for devices STM32F103xB and STM32F401xC.

## [1.5.0] - 2024-07-22

### Added

- SPI module for devices STM32F030x6, STM32F103xB, STM32F401xC.

## [1.4.0] - 2024-07-18

### Added

- I2C module for devices STM32F030x6, STM32F103xB, STM32F401xC.

## [1.3.0] - 2024-07-07

### Added

- ADC module for devices STM32F030x6, STM32F103xB, STM32F401xC.

### Fixed

- USART Wrappers are now declared as static.

## [1.2.0] - 2024-06-28

### Added

- USART module for devices STM32F030x6, STM32F103xB, STM32F401xC.

## [1.1.0] - 2024-06-25

### Added

- STM32F030x6 support for timer module

### Changed

- Device specific PCC checks updated, taking STM32F030x6 in account. (timer module)
- Complimentary PWM output channels can be toggled and checked now. (timer module)

## [1.0.1] - 2024-06-23

### Added

- Enable check functions for timer interrupts. (timer module)

### Fixed

- Convenient IRQ implementations now use if-else-if conditional statements instead of successive if statements for multiple interrupts. (timer module)
- Convenient IRQ implementations now check if the interrupts are enabled as well, if multiple interrupts are handled in the body. (timer module)
 
## [1.0.0] - 2024-06-22
  
### Added
 
- Timer/interrupt utility module for STM32F401xC and STM32F103xB.
- MIT License.
