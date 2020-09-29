# Zracker

#### Zracker is a Zip File Password BruteForcing Utility Tool based on CPU-Power.
>- Yet available for Linux only ...
>- Supports WordList Mode only but will surely get an Update with BruteForce Mode

# Features

### [1] Auto Updater :tada:

* Automatically checks for updates when you start the script, and Downloads and Installs if any update is available so.

### [2] Utilises the Power of CPU-Cores :sunglasses:

* Can utilise Maximum no. of Cores available.
  - This means increases the process of cracking of zip passwords by opening different processes on different independent cores.
  - What this basically does is Split the inputted words from the given WordList and divides them in the no. of Cores Available or Selected and distributes that splitted list among all selected independent cores and work simultaneously ...


# Pre-Requisites

#### Minimal requirements just include:
- Python 3.xx

# Disclaimer

#### uhm!.. Well don't use it for **Illegal** purposes.

# Installation

### [1] Download Zracker, either using git clone :
`git clone https://github.com/devim-stuffs/Zracker.git`
### or directly download and extract the zip file.

### [2] Change current Directory to `Zracker` :
`cd Zracker/`

### [3] After that, just run the Python Script named `zracker.py` like :
`python3 zracker.py`
  * It will automatically take care of Python PIP Dependencies and would install them.
    - Well the `requirements.txt` file is included inside file `backend/`, incase ...

# To-Do's

  - [x] Progress Percentage Show.
  - [ ] BruteForce mode.
