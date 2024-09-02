# 90-Minute Timer App

A simple and functional timer application built with React.js. The app features a 90-minute countdown timer, a fireworks animation, and an alarm sound effect when the timer ends. Users can start the timer with a single click and interact with the timer functionalities.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- **Start Timer**: Begins a 90-minute countdown with a single button click.
- **Display Remaining Time**: Dynamically shows the time left in minutes and seconds.
- **Fireworks Animation**: Displays a fireworks animation when the timer ends.
- **Alarm Sound**: Plays a sound effect (firecracker sound) when the timer reaches zero.
- **Stop Alarm**: Allows the user to stop the alarm sound manually.

## Demo
You can view a live demo of the project [here](https://main--90-mins-timer.netlify.app/).

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/harryjcpy/90-mins-timer.git
    ```
   
2. **Navigate to the project directory:**
    ```bash
    cd 90-mins-timer
    ```
   
3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Start the development server:**
    ```bash
    npm run dev
    ```
   
The app will run locally on [http://localhost:3000](http://localhost:3000).

## Usage

1. Click the **Start Timer** button to begin the 90-minute countdown.
2. The remaining time will be displayed on the screen.
3. When the timer reaches zero, an alarm sound will play, and a fireworks animation will be triggered.
4. To stop the alarm sound, click the **Alarm Off** button.

## Components

### 1. `TimerButton.jsx`
- The main component that handles the timer logic, including starting the timer, managing state, and interacting with the alarm and fireworks animation.

### 2. `Fireworks.jsx`
- A component that renders a fireworks animation when the timer ends.

## Technologies Used
- **React.js**: Frontend library for building the user interface.
- **CSS3**: Styling for animations and visual effects.
- **JavaScript (ES6+)**: Logic for managing the timer and animations.
- **HTML5**: Structuring the application layout.

## Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request. Please ensure that your code follows the project's coding style and conventions.

## Acknowledgments

- Sound effects from [Click Here](https://pixabay.com/sound-effects/search/fireworks/).
- Fireworks animation from [Click Here](https://codepen.io/tag/firework).
