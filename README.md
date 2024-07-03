# Atlas II Robotic Arm Simulation

This project simulates the movements of the Atlas II robotic arm using WebGL and Three.js. It aims to replicate the unique design and functionality of the Atlas II arm developed by LJ Electronics Ltd. More detailed information can be found on Neil Fazakerley's BeebControl website: http://www.riscy.uk/beebcontrol/arms/atlas/index.html.

![Demo](/images/atlas.png)

## Where to Use

This simulation is also available at [Diggedy Pomme's Arm11 Simulator](https://diggedypomme.com/stu/arm11.html).

## About

The Atlas II robotic arm was known for its unconventional design and internal computational capabilities, setting it apart from other robotic arms of its time. This simulation project attempts to recreate its movements and functionalities in a virtual environment using WebGL and Three.js.

## Setup Instructions

To run the simulation locally on your machine, follow these steps:

1. **Clone the repository**:
git clone https://github.com/your-username/atlas-robotic-arm.git

cd atlas-robotic-arm

3. **Start a local server**:

Since modern browsers restrict certain functionalities when opening HTML files locally due to security reasons, you need to start a local server to run the simulation. Use Python's built-in HTTP server for this purpose:
python -m http.server


3. **Access the simulation**:

Open your web browser and navigate to `http://localhost:8000/` (or another port specified by Python if different). This will serve the `index.html` file, allowing you to interact with the Atlas II robotic arm simulation.

## Usage

- **Single Command Execution**:
- Enter a command in the input field (e.g., A50, B100, C0) and click `OK` to execute.
- **Batch Command Execution**:
- Enter multiple commands sequentially in the command box and click `Run Commands` to execute them one by one.
- **Visualization**:
- Use mouse controls to orbit around the robotic arm and observe its movements from different angles.

## Commands

The following commands can be used to control the robotic arm:

- **A0 to A100**: Rotate base (pan) from 0 to 100 degrees.
- **B0 to B100**: Tilt head from 0 to 100 degrees.
- **C0 to C100**: Translate arm from 0 to 100 units.
- **D0 to D100**: Tilt wrist from 0 to 100 degrees.
- **E0 to E100**: Rotate hand from 0 to 100 degrees.
- **F0 to F100**: Translate fingers from 0 to 100 units.
- **G0 to G100**: (Optional) Translate finger L from 0 to 100 units.
- **H0 to H100**: (Optional) Translate finger R from 0 to 100 units.

