# Pygame Docs 2.0
A newer update version of the Pygame docs based off of: https://www.pygame.org/docs/.

## Installation
To install Pygame, simply run the following command in your terminal:
```
pip3 install pygame
```
If you get any errors make sure you have installed [Python](https://www.python.org/downloads/) and [pip](https://github.com/pypa/pip).

### Installing Python

<details>
<summary>Click me if you want to install Python!</summary>
<br>
#### For Windows

1. **Download Python:**
   - Visit the [official Python website](https://www.python.org/downloads/).
   - Click on the latest version for Windows. The site will usually suggest the best version for your system.

2. **Run the Installer:**
   - Open the downloaded `.exe` file.
   - **Important:** Check the box that says “Add Python to PATH” before clicking “Install Now.” This makes it easier to run Python from the command line.
   - Choose “Install Now” or customize the installation as needed by selecting “Customize Installation.”

3. **Verify Installation:**
   - Open Command Prompt and type:
     ```sh
     python3 --version
     ```
   - You should see the installed Python version.

#### For macOS

1. **Download Python:**
   - Go to the [official Python website](https://www.python.org/downloads/) and download the macOS installer for the latest version of Python.

2. **Run the Installer:**
   - Open the downloaded `.pkg` file and follow the instructions to install Python.

3. **Verify Installation:**
   - Open Terminal and type:
     ```sh
     python3 --version
     ```
   - You should see the installed Python version.

4. **Note:** macOS comes with Python 2.x installed by default. The `python3` command is used to access Python 3.x.

#### For Linux

1. **Use a Package Manager:**
   - Most Linux distributions come with Python pre-installed. If you need a newer version or want to ensure Python is installed, you can use the package manager for your distribution.
   
   - **Ubuntu/Debian:**
     ```sh
     sudo apt update
     sudo apt install python3
     ```

   - **Fedora:**
     ```sh
     sudo dnf install python3
     ```

   - **Arch Linux:**
     ```sh
     sudo pacman -S python
     ```

2. **Verify Installation:**
   - Open Terminal and type:
     ```sh
     python3 --version
     ```
   - You should see the installed Python version.

</details>

### Installing `pip`

<details>
<summary>
Click me if you want to install pip!
</summary>
<br>


`pip` is the package installer for Python. Here’s how to install it on different operating systems.

#### For Windows

1. **Ensure Python is Installed:**
   - Check if Python is installed by running `python --version` in Command Prompt. If it’s not installed, download and install Python from the [official Python website](https://www.python.org/downloads/).

2. **Download `get-pip.py`:**
   - Visit the `get-pip.py` script page: [get-pip.py](https://bootstrap.pypa.io/get-pip.py).
   - Right-click and choose "Save As" to download the file.

3. **Install `pip`:**
   - Open Command Prompt and navigate to the directory where you downloaded `get-pip.py`.
   - Run the following command:
     ```sh
     python get-pip.py
     ```
   - This will install `pip` for your Python installation.

4. **Verify Installation:**
   - After installation, verify by running:
     ```sh
     pip --version
     ```

#### For macOS and Linux

1. **Ensure Python is Installed:**
   - Check if Python is installed by running `python3 --version` or `python --version` in Terminal. If it’s not installed, you can install it using a package manager like Homebrew on macOS or `apt` on Ubuntu.

2. **Install `pip` (if it’s not already installed):**
   - For Python 3.4 and later, `pip` should come pre-installed. You can verify it by running:
     ```sh
     pip3 --version
     ```
   - If `pip` is not installed, you can use the `ensurepip` module:
     ```sh
     python3 -m ensurepip --upgrade
     ```

   - Alternatively, you can use the `get-pip.py` script as mentioned above:
     ```sh
     curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
     python3 get-pip.py
     ```

3. **Verify Installation:**
   - Confirm the installation by running:
     ```sh
     pip3 --version
     ```
</details>




## Checks
After running this, to check the pygame version, run the following command in your terminal:
```
python3
```
Then,
```
import pygame
```
If you get an output similar to this, then retry installing;
```
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'pygame'
```
If not, you probably got something like this and you are all good to start your Pygame journey!
```
pygame 2.6.0 (SDL 2.28.4, Python 3.12.5)
Hello from the pygame community. https://www.pygame.org/contribute.html
```