# install-nethunter-termux

This script helps you install an older, stable version of Kali Linux Nethunter on Termux. The new Kali Linux Nethunter has a known issue (`dpkg` errors during tasks), and this script fixes that by installing a functional older version of Nethunter.

## Why Use This Script?

The latest version of Kali Linux Nethunter on Termux often throws errors during installation or while using `dpkg`, as shown below:

### Error Example:
- **dpkg Error in Latest Version**  
  ![Error](error.jpeg)

To overcome these issues, this script installs a tested and stable older version of Kali Linux Nethunter.

---

## Requirements

Make sure you have Termux installed on your device. This script is designed to work seamlessly within Termux.

---

## Installation Steps

1. Install Git in Termux:

    ```bash
    pkg install git
    ```

2. Clone the repository:

    ```bash
    git clone https://github.com/Mr-Risov/Install-nethunter-termux/
    ```

3. Navigate to the project directory:

    ```bash
    cd Install-nethunter-termux/
    ```

4. Make the script executable:

    ```bash
    chmod +x install-nethunter-termux
    ```

5. Run the script to install Nethunter:

    ```bash
    ./install-nethunter-termux
    ```

---

## Installation Screenshots

- **During Installation**:  
  ![Installing](installing.jpeg)

- **After Installation**:  
  ![Installed](Installed.jpeg)

---

## Usage

After successfully installing Nethunter, follow these steps to use it:

1. Start Nethunter:

    ```bash
    nh
    ```

2. Start the GUI with Kex:

    ```bash
    nh kex &
    ```

3. Gain root access for administrative tasks:

    ```bash
    sudo su
    ```

4. Set or update the Nethunter password:

    ```bash
    nh password
    ```

---

## Common Errors in Latest Version and How This Script Fixes Them

### 1. `dpkg` Errors
- **Error Example:**  
  ![Error Example](error.jpeg)  
  This error often occurs when using the latest version of Nethunter. The script avoids this issue by installing a functional older version of Nethunter.

### 2. Dependency Installation Issues
- **Problem:** Some dependencies fail to install, causing the latest Nethunter version to break.
- **Solution:** The stable version provided by this script includes all required dependencies pre-configured.

---

## Notes

- Ensure you have at least 5GB of free storage before starting the installation.
- If you encounter issues or need help, feel free to open an issue on this repository.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
