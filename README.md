# STM32 Watchdog Demonstration Project

https://github.com/Hoang-Phuc-Tran/EMBEDDED-SYSTEMS--Watchdogs/assets/120700092/fb4fee11-be64-40c8-92fa-9fad5094db25


Welcome to the STM32 Watchdog Demonstration Project! In this repository, we introduce a simple yet insightful demonstration that showcases the functionality of the hardware watchdog on the STM32 board.

## Quick Overview

Explore the power of the hardware watchdog with our new _xxWatch demonstration. Through this project, you'll witness how the hardware watchdog can impact the operation of the STM32 board, ensuring system stability and responsiveness.

## Project Highlights

- **Watchdog Initialization**: Begin by creating a function called `_xx_watchdog_start` in assembly. This function initializes and starts the hardware watchdog, setting the foundation for watchdog-controlled behavior.

- **Customizable Duration**: Experiment with prescaler and reload values to determine the watchdog duration. Configure the watchdog timeout via the _xxWatch menu item, allowing you to tailor the behavior to your specific needs.

- **Blinking LED Demonstration**: Utilize the system tick timer to orchestrate an engaging LED demonstration. All 8 LEDs will blink on and off simultaneously, showcasing the watchdog's impact on system behavior.

- **User Button Interaction**: The user button becomes a pivotal element of the demonstration. When not pressed, the watchdog is refreshed appropriately. However, once the user button is pressed, the watchdog refresh ceases, and the blinking LED sequence continues.

## Example

For instance, consider the command: xxWatch timeout delay<br/><br/>
The board will execute the blinking light demo with the watchdog enabled for the timeout you specify. You will
need to determine what the units of timeout are. Delay should be in milliseconds, representing the amount of time
the LEDs spend ON, and then OFF.
