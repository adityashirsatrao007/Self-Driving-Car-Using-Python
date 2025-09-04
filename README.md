# Self-Driving-Car-Virtual

A Virtual Self-Driving Car simulation built with Python and Pygame.

This project allows you to simulate a self-driving car navigating different tracks. It is a beginner-friendly introduction to computer vision, path planning, and automation concepts using Python.

## Features

- **Multiple Tracks:** The repository includes 6 different track images. You can easily switch between tracks to test the car's navigation on various layouts.
- **Customizable:** Modify the car's speed, sensors, and behavior to experiment with different self-driving strategies.
- **Visual Simulation:** Real-time rendering using Pygame, allowing you to observe the car's decision-making process.
- **Simple Controls:** Run the simulation with a few commands. No complex setup required.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Installation

Install the required Python package:

```bash
pip install pygame
```

### Running the Simulation

1. Clone the repository:
    ```bash
    git clone https://github.com/adityashirsatrao007/Self-Driving-Car-Using-Python.git
    cd Self-Driving-Car-Using-Python
    ```

2. Run the main Python file (typically named `main.py` or similar):
    ```bash
    python main.py
    ```

3. The simulation window will open with the default track. You can change the track image by editing the code:
    ```python
    TRACK = 'tracks/track6.png'  # Change the number to select a different track (1 to 6)
    ```

## How to Change Tracks

In the code, look for the section that loads the track image. Modify the filename to choose from `track1.png` to `track6.png`. Each track presents different navigation challenges for the self-driving car.

![Track Example](https://user-images.githubusercontent.com/61585443/182076051-4cc5a446-006a-469d-ba5f-5508afb1a0e7.png)

## Project Structure

```
Self-Driving-Car-Using-Python/
│
├── main.py             # Entry point for simulation
├── car.py              # Car logic and movement
├── tracks/             # Track images (track1.png to track6.png)
├── assets/             # Additional assets (car image, etc.)
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
```

## Contributing

Pull requests are welcome! If you have ideas for new features, bug fixes, or improvements, feel free to fork the repository and submit a PR.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Pygame](https://www.pygame.org/) - For graphics and game logic.

---

Enjoy experimenting with the Self-Driving Car simulation!
