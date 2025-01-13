# Install-nethunter-termux

This script helps you install an older, stable version of Kali Linux Nethunter on Termux. The latest version of Kali Linux Nethunter often encounters issues such as `dpkg` errors, and this script resolves them by installing a functional older version.

---

## Why Use This Script?

The latest version of Kali Linux Nethunter on Termux throws errors during installation or while using `dpkg`, as shown below:

### **Error Example**
![dpkg Error](https://i.ibb.co/4PKK5NP/IMG-20250113-102242.jpg)  

To avoid this, the script installs a stable older version of Nethunter that has been thoroughly tested.

---

## Requirements

- **Termux** installed on your device.
- At least **5GB of free storage**.

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

- **During Installation**  
  ![Installing](https://i.ibb.co/N66PBjf/Screenshot-2025-01-13-10-12-34-945-com-termux.jpg)  

- **After Installation**  
  ![Installed](https://i.ibb.co/QnbfryS/010-NH-Rootless-Installation-Start-s.png)

- **Using kex**
  ![kex](https://i.ibb.co/0hM4kFJ/020-NH-Rootless-Ke-X-s.png)

---

## Usage

After successfully installing Nethunter, follow these steps to use it:

1. **Start Nethunter:**

    ```bash
    nh
    ```

2. **Launch the GUI with Kex:**

    ```bash
    nh kex &
    ```

3. **Gain Root Access:**

    ```bash
    sudo su
    ```

4. **Set or Update Password:**

    ```bash
    nh password
    ```

---

## Common Errors in Latest Version

### 1. **`dpkg` Errors**
- **Error Example**:  
  ![dpkg Error](https://i.ibb.co/4PKK5NP/IMG-20250113-102242.jpg)  
  The error occurs due to compatibility issues in the latest version. This script resolves the issue by installing a stable version.

### 2. **Dependency Issues**
- Some dependencies fail to install in the latest version. The older version used in this script includes all necessary dependencies.

---

## Notes

- This script is intended for Termux users seeking a functional version of Kali Linux Nethunter.
- If you face any issues, please open an issue on this repository.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
