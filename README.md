# ApexPlus-Technologies
# React Scenario Simulation Application

This project is a React.js application that allows users to create, display, update, and delete scenarios and vehicles. Each scenario can have multiple vehicles, and the vehicles can move within a simulated environment based on user input.

## Features

- Create, display, update, and delete scenarios and vehicles.
- Scenarios have the following fields:
  - Scenario ID
  - Scenario Name
  - Time
- Vehicles have the following fields:
  - Vehicle ID
  - Vehicle Name
  - Initial Position (X, Y)
  - Speed
  - Direction (Towards, Backwards, Upwards, Downwards)
- Data storage is implemented using json-server.

## Installation

Follow these steps to install and run the application:

1. Clone the repository from GitHub:


2. Navigate to the project directory:


3. Install the dependencies:


4. Start the json-server:


5. In a separate terminal, start the React development server:


6. The application should now be running on `http://localhost:3000`.

## Usage

1. Open the application in your browser at `http://localhost:3000`.
2. Use the sidebar to navigate to the Home page.
3. In the Home page, select a scenario you have created to start the simulation.
4. Click the "Start Simulation" button to initiate the movement of vehicles based on their speed and direction.
5. The vehicles will move within the simulated environment until the scenario time elapses.
6. If a vehicle goes outside the container, it will be hidden.
7. To add a new vehicle, click the "Add Vehicle" button and provide the necessary information, ensuring that the positions do not exceed the graph container's size.
8. Perform any other desired actions using the provided user interface.

## Contributing

Thank you for considering contributing to this project. To contribute, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name.
3. Make your desired changes.
4. Commit and push your changes to your forked repository.
5. Submit a pull request, explaining the changes you have made.

## License

This project is licensed under the [MIT License](LICENSE).

