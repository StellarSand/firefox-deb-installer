# firefox-deb-installer

Bash script to automate the installation of the official Firefox `.deb` package for Debian-based distributions, as documented by Mozilla [here](https://support.mozilla.org/en-US/kb/install-firefox-linux#w_install-firefox-deb-package-for-debian-based-distributions-recommended).

**Why use this instead of installing Firefox via the APT repo, Flatpak, or Snap?**
<br>On some Debian-based distros (like Kali Linux), the APT repo only provides Firefox ESR by default. On Ubuntu, Firefox is installed as a Snap package by default, but some users may prefer to install it from the APT repo. However, the Firefox package in the Ubuntu APT repo reinstalls Firefox as a Snap package.
<br>Using this script you can install & update to the latest non‑ESR Firefox directly from the APT repo.

## Contents
- [Usage](#usage)
- [Issues](#issues)
- [Contributing](#contributing)
- [License](#license)



## Usage
> [!NOTE]
> On Ubuntu, remove the Firefox Snap package before running the install script.

1. Clone this repo:
    ```bash
    git clone https://github.com/StellarSand/firefox-deb-installer.git
    ```

2. Move into the project directory:
    ```bash
    cd firefox-deb-installer
    ```

3. Give executable permissions to the script:
    ```bash
    chmod +x install
    ```

4. Run the install script:
    ```bash
    ./install
    ```



## Issues
If you find bugs or have suggestions, please report it to the [issue tracker](https://github.com/StellarSand/firefox-deb-installer/issues). 
- Please search for existing issues before opening a new one. Any duplicates will be closed.



## Contributing
Pull requests can be submitted [here](https://github.com/StellarSand/firefox-deb-installer/pulls).



## License
This project is licensed under the terms of [GPL v3.0 license](https://github.com/StellarSand/firefox-deb-installer/blob/main/LICENSE).