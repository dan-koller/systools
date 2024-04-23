# SysTools

This repository contains a set of Python scripts to monitor systems and gather information about them like battery information or a system overview.

## Requirements

-   Python 3.9 or higher
-   Required Python packages listed in `requirements.txt`

## Get started

1. Clone the repository

    ```bash
    git clone https://github.com/dan-koller/systools
    ```

2. Create a new virtual environment & activate it

    ```bash
    python3 -m venv .venv && source .venv/bin/activate
    ```

    > On Windows, open a command prompt and run `.venv\Scripts\activate.bat`

3. Install the required Python packages

    ```bash
    pip3 install -r requirements.txt
    ```

4. Run the script you want to use

    ```bash
    python3 <script_name.py>
    ```

_\*) You might need to use python and pip instead of python3 and pip3 depending on your system._

## Scripts

-   `battery.py`: Get information about the battery of your system (if available)
-   `system_monitor.py`: Monitor the system and display information about the CPU, memory, disk, and network usage

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
