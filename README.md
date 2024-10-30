# Simple PHP Page for AWS EC2 Deployment

This repository contains a simple PHP page designed to be deployed on AWS EC2. The page connects to a MySQL database, allows users to add employee data, and displays the data in a table.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Authors](#authors)
- [License](#license)

## Overview
This project is a basic PHP web application that connects to a MySQL database. It allows users to add employee names and addresses through a form and displays the stored data in a table.

## Features
- **Form Input**: Add employee names and addresses.
- **Data Display**: Display employee data in a table.
- **Database Interaction**: Connect to MySQL database to store and retrieve data.

## Prerequisites
- **PHP**: Ensure PHP is installed on your server.
- **MySQL**: A MySQL database to store employee data.
- **AWS EC2 Instance**: An EC2 instance to deploy the application.

## Installation
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/simple-php-page.git
   cd simple-php-page
   ```

2. **Set up the MySQL database**:
   - Create a MySQL database and update the `dbinfo.inc` file with your database credentials.

3. **Deploy to AWS EC2**:
   - Launch an EC2 instance and install a web server (e.g., Apache) and PHP.
   - Transfer the project files to the EC2 instance.
   - Ensure the web server is configured to serve the PHP files.

## Usage
1. **Access the web page**:
   - Open a web browser and navigate to the public IP address of your EC2 instance.

2. **Add employee data**:
   - Use the form on the page to add employee names and addresses.

3. **View employee data**:
   - The added data will be displayed in a table below the form.

## Code Structure
- **`index.php`**: Main PHP file containing the form and logic for database interaction.
- **`dbinfo.inc`**: Contains database connection information.

## Authors
- Paulo Vinicius Martimiano de Oliveira

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
