
# Project Name

## Overview

This project is a Python application designed to [briefly describe the purpose of the project]. The repository includes the main Python script `main.py`, configuration data in `data.json`, and dependency management handled by Poetry (`poetry.lock`).

## Features

- **Feature 1:** [Describe a key feature]
- **Feature 2:** [Describe another feature]
- **Feature 3:** [Describe an additional feature]

## Requirements

- Python 3.x
- Poetry (for dependency management)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**
   Use Poetry to install the necessary dependencies listed in `pyproject.toml` and `poetry.lock`.
   ```bash
   poetry install
   ```

## Usage

1. **Prepare configuration:**
   Ensure your `data.json` file is correctly set up with the necessary credentials:
   ```json
   {
       "GOOGLE": {
           "email": "angela@gmail.com",
           "password": "your_google_password"
       },
       "X": {
           "email": "angela@gmail.com",
           "password": "your_x_password"
       },
       "INSTAGRAM": {
           "email": "angela@gmail.com",
           "password": "your_instagram_password"
       }
   }
   ```

2. **Run the main script:**
   Execute the `main.py` script to start the application.
   ```bash
   poetry run python main.py
   ```

## Configuration

- **data.json:** Contains the email and password information for different services (Google, X, Instagram). Ensure this file is secure and not shared publicly.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License 

## Contact

For any issues or questions, please contact [juanzamdev@gmail.com](mailto:juanzamdev@gmail.com).
