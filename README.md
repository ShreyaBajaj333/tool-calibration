# Calibration Tool Management System

Calibration Tool Management System is a web-based application for managing and tracking the calibration status of tools and equipment in an industrial setting.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The Calibration Tool Management System simplifies the process of tracking and managing tool calibration data in industrial plants. It allows users to enter calibration information, set reminders for upcoming calibrations, and search for tools based on various criteria.

## Features

- User-friendly web interface.
- Add, edit, and delete tool calibration records.
- Set reminders for upcoming calibrations.
- Search for tools by name, unique identifier, or type.
- Supports multiple plant locations with different areas.

## Getting Started

To get started with the Calibration Tool Management System, follow these steps:

### Prerequisites

Before you begin, ensure you have the following software/tools installed:

- Python 3.x
- Flask
- SQLAlchemy
- SQLite
- Git (optional, for cloning the repository)

### Installation

1. Clone the repository:

   ```bash
   $ git clone https://github.com/ShreyaBajaj333/tool-calibration.git
   $ cd calibration-tool-management
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   $ python -m venv venv
   $ source venv/bin/activate
   ```

3. Install the required Python packages:

   ```bash
   $ pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   $ python app.py
   ```

The application should now be running locally. Access it in your web browser at `http://localhost:8081`.

## Usage

1. Open the application in your web browser.

2. Enter calibration information for your tools and equipment.

3. Set reminders for upcoming calibrations.

4. Search for tools using the provided search functionality.

## Contributing

We welcome contributions from the community. To contribute to the Calibration Tool Management System, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   $ git checkout -b feature-name
   ```

3. Make your changes and commit them:

   ```bash
   $ git commit -m "Add feature or fix bug"
   ```

4. Push your changes to your fork:

   ```bash
   $ git push origin feature-name
   ```

5. Open a pull request on the main repository.

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) when contributing.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to acknowledge the following libraries and tools used in this project:

- [Flask](https://flask.palletsprojects.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Bootstrap](https://getbootstrap.com/)

