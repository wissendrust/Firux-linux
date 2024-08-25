# Installing FiruxLinux with FLUPI

Welcome to the FiruxLinux installation guide using the FLUPI method! This method simplifies the installation process by avoiding the need to download a complete ISO image. Instead, we will download the base operating system and then install the necessary packages.

## Requirements

- Internet connection.
- An existing Linux operating system (any distribution compatible with `pacman`).

## Installation Steps

1. **Prepare the Environment**

   Ensure your current operating system is up-to-date and that `pacman` is available. If you are using an Arch Linux-based distribution, `pacman` should already be installed.

2. **Download the FLUPI Installer**

   Download the FLUPI package from the official FiruxLinux page or repository. You can use `wget` or `curl` for this:

   bash
   wget https://example.com/path/to/flupi-installer.tar.gz
   

3. **Extract the Package**

   Extract the downloaded file:

   bash
   tar -xzvf flupi-installer.tar.gz
   

4. **Run the Installer**

   Navigate to the extracted directory and run the installation script:

   bash
   cd flupi-installer
   sudo ./install.sh
   

5. **Configure the Installation**

   During installation, the script will prompt you to select some settings and options. Follow the on-screen instructions to configure your FiruxLinux installation.

6. **Install Additional Packages**

   Once the base installation is complete, you can install any additional packages needed for your environment. Use the following command to install the FiruxLinux base package:

   bash
   sudo pacman -S firux-base
   

   To install any other packages, use:

   bash
   sudo pacman -S <package-name>
   

7. **Reboot the System**

   After completing the installation and configuration, reboot your system to apply the changes:

   bash
   sudo reboot
   

8. **First Boot**

   Upon rebooting, you should see the new FiruxLinux operating system. Log in with the credentials you configured during the installation.

## Common Issues

- **Cannot connect to the Internet**: Ensure that your internet connection is working properly and that your network is configured.
- **Errors during installation**: Check the error messages and ensure all steps have been completed correctly.

## Support

If you encounter any problems or have questions, feel free to contact FiruxLinux support via email: support@firuxlinux.org.

Thank you for choosing FiruxLinux!
