# Fluffy Goggles

## Setup Instructions for Raspberry Pi

To get started with setting up Fluffy Goggles on your Raspberry Pi, please follow the instructions below:

### Prerequisites
- Ensure that you have a Raspberry Pi 3 or later.
- An internet connection.
- Basic knowledge of terminal commands.

### Installation Steps
1. Update your system packages:
   ```bash
   sudo apt update && sudo apt upgrade
   ```

2. Install necessary dependencies:
   ```bash
   sudo apt install -y build-essential git
   ```

3. Clone the repository:
   ```bash
   git clone https://github.com/alex-workhard/fluffy-goggles.git
   cd fluffy-goggles
   ```

4. Compile the project:
   ```bash
   make
   ```

5. (Optional) Install the application:
   ```bash
   sudo make install
   ```

## Running Fluffy Goggles
To run the application, use the following command:
```bash
fluffy-goggles
```

## Troubleshooting
- If you encounter any issues, please check the `issues` section of the GitHub repository for solutions or open a new issue for assistance.

Enjoy using Fluffy Goggles!