# Elevator App

A simple web-based elevator app that simulates the operation of an elevator and handles events generated when building occupants use it. Built using HTML, CSS, and JavaScript.

![Elevator App Screenshot](screenshot.png)

## Features

- Cross-section diagram of a building with four floors, elevator shaft, elevator, and floor buttons
- Elevator control panel with buttons for each floor
- Clickable floor buttons to call the elevator
- Queuing and servicing of elevator call requests in the order they were clicked
- Elevator movement visualization
- Clickable elevator control panel buttons to select the desired floor
- Elevator pause for 5 seconds waiting for a floor button to be clicked before processing the next request
- Elevator returns to the first floor when there are no requests to process

## Installation

1. Clone the repository or download the source code:

git clone https://github.com/yallendekoker/elevator-app.git

2. Change to the project directory:

cd elevator-app

3. Open the `index.html` file in your web browser.

## Usage

1. Click the up and down buttons on any floor to call the elevator.
2. The elevator moves to the called floor and pauses for 5 seconds.
3. Click a button on the elevator control panel to select the floor the elevator should travel to.
4. The elevator moves to the selected floor and pauses for 5 seconds.
5. If no buttons are clicked within 5 seconds, the elevator processes the next call request or returns to the first floor if there are no requests.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.