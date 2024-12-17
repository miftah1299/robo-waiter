# Robo Waiter

Robo Waiter is a Flask-based application designed to simulate a robotic waiter navigating a restaurant to deliver food orders. The application leverages the A\* search algorithm to determine the most efficient path from the kitchen to the tables, ensuring timely and accurate delivery of food items.

## Features

-   Simulates a robotic waiter in a restaurant environment
-   Uses the A\* search algorithm for pathfinding
-   Efficiently calculates the optimal path for food delivery
-   Flask-based web application

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/robo-waiter.git
    ```

2. Navigate to the project directory:
    ```sh
    cd robo-waiter
    ```
3. Create and activate a virtual environment:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

5. Install Flask-CORS:
    ```sh
    pip install flask-cors
    ```

## Usage

1. Run the Flask application:

    ```sh
    python -m flask --app main run --debug
    ```

2. Open your web browser and navigate to http://127.0.0.1:5000 to access the application.

3. Run the server in debugging mode by executing the following command:

    ```sh
    flask --app main run --debug
    ```

4. Navigate to the `ui` folder and start the live server using the VSCode Live Server extension.

Ensure you have Python installed on your machine before running the project.

Enjoy using the Robo Waiter!
