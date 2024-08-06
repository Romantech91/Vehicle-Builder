# Vehicle Builder CLI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

A command-line interface (CLI) for building and managing different types of vehicles including cars, trucks, and motorbikes. This Cli also lets you perform actions and manage their attributes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Video walk through](video-walk-through)
- [Credits](#credits)
- [Features](#features)
- [Vehicle Classes](#vehicle-classes)
  - [Vehicle](#vehicle)
  - [Car](#car)
  - [Truck](#truck)
  - [Motorbike](#motorbike)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [License](#license)
- [Questions](#questions)

## Installation

node.js
npm install
npm run start

## Usage

To run this CLI, follow these steps:

1. Run the scripts using npm i.

   - npm i

2. Starting CLI:

   - npm run start

3. You will be prompted to either create a new vehicle or select an existing one to perform actions on.

## Video walk through

For a visual walk through on how to use the application, click on to watch the video.

## Credits

This project was created by @Romantech91

## Features

- Create and manage cars, trucks, and motorbikes.

- Perform various actions on vehicles, such as starting, accelerating, decelerating, stopping, turning, reversing, towing (for trucks), and doing a wheelie (for motorbikes).

- Print detailed information about each vehicle.

## Vehicle Classes

### Vehicle

Base class for all vehicle types, including common properties and methods

#### Properties

      - vin: Vehicle indentification number
      - color: Color of the vehicle
      - make: Make of the vehicle
      - model: Model of the vehicle
      - year: Year of manufacture
      - weight: Weight of the vehicle
      - topSpeed: Top speed of the vehicle

#### Methods

      - printDetails: Prints the details of the vehicle
      - start: Starts the vehicle
      - accelerate: Accelerates the vehicle by a specified amount
      - decelerate: Decelerates the vehicle by a specified amount
      - stop: Stops the vehicle
      - turn: Turns the vehicle in the specified direction
      - reverse: Reverses the vehicle

### Car

No additional properties or methods

### Truck

Additional property and method

#### Properties

      - towingCapacity: The maximum weight the truck can tow

#### Methods

      - tow: Tows the specified vehicle

### Motorbike

Additional property and method

#### Properties

      - wheels: An array of wheel objects representing the motorbike's wheels

#### Methods

      - wheelie: Logs a message indicating the motorbike is doing a wheelie

## How to Contribute

If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

## Tests

Currently, there are no automated tests for this project. You can test the application manually by running the script and verifying the output.

## License

MIT

## Questions

If you have any questions, please reach out to me at victor_roman1198@yahoo.com or visit my GitHub profile at @Romantech91.
