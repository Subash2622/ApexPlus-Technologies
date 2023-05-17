# ApexPlus-Technologies
React Scenario Simulation Application
This project is a React.js application that allows users to create, display, update, and delete scenarios and vehicles. Each scenario can have multiple vehicles, and the vehicles can move within a simulated environment based on user input.

Features
Create, display, update, and delete scenarios and vehicles.
Scenarios have the following fields:
Scenario ID
Scenario Name
Time
Vehicles have the following fields:
Vehicle ID
Vehicle Name
Initial Position (X, Y)
Speed
Direction (Towards, Backwards, Upwards, Downwards)
Data storage is implemented using json-server.
Installation
Follow these steps to install and run the application:

Clone the repository from GitHub:

bash
Copy code
git clone [repository URL]
Navigate to the project directory:

bash
Copy code
cd react-scenario-simulation
Install the dependencies:

Copy code
npm install
Start the json-server:

css
Copy code
json-server --watch db.json --port 3001
In a separate terminal, start the React development server:

sql
Copy code
npm start
The application should now be running on http://localhost:3000.

Usage
Open the application in your browser at http://localhost:3000.
Use the sidebar to navigate to the Home page.
In the Home page, select a scenario you have created to start the simulation.
Click the "Start Simulation" button to initiate the movement of vehicles based on their speed and direction.
The vehicles will move within the simulated environment until the scenario time elapses.
If a vehicle goes outside the container, it will be hidden.
To add a new vehicle, click the "Add Vehicle" button and provide the necessary information, ensuring that the positions do not exceed the graph container's size.
Perform any other desired actions using the provided user interface.
Contributing
Thank you for considering contributing to this project. To contribute, follow these steps:

Fork the repository on GitHub.
Create a new branch with a descriptive name.
Make your desired changes.
Commit and push your changes to your forked repository.
Submit a pull request, explaining the changes you have made.
License
This project is licensed under the MIT License.
