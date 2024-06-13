# Installation and Configuration of Terminal

## Installation

### 1. Install Windows Terminal

To begin, download and install "Windows Terminal" from the Microsoft Store.

### 2. Install a Font

Next, install a font for your terminal. You can find fonts on the [Nerd Fonts](https://www.nerdfonts.com/) website.

We recommend using the "ProFont Nerd Font," which you can download [here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/ProFont.zip).

To install the font:
1. Unzip the downloaded file.
2. Select the `.ttf` files.
3. Right-click and select "Install."

### 3. Install Starship for a Custom Prompt

To get a more aesthetic prompt, we will install Starship. Follow the instructions on the [Starship](https://starship.rs/guide/) website.

To install Starship via Chocolatey:
1. Open a PowerShell terminal as an administrator.
2. Run the following command to install Chocolatey:

    ```powershell
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    ```

3. Then, install Starship with the following command:

    ```powershell
    choco install starship
    ```

4. To configure Starship with PowerShell, open the configuration file by typing the following command:

    ```powershell
    notepad $PROFILE
    ```

5. Add the following line at the end of the file:

    ```powershell
    Invoke-Expression (&starship init powershell)
    ```

## Configuration

### 1. Access Terminal Settings

To configure the terminal:
1. Click on the arrow to the right of the tab.
2. Select "Settings."

### 2. Change the Font

To change the font:
1. Go to the `defaults` section.
2. Then, go to `appearance`.
3. Change the `fontFace` value to the name of the font you installed.

### 3. Change the Color Scheme

To change the color scheme:
1. In the settings, go to `colorScheme`.
2. Change the `colorScheme` value to the name of the desired color scheme. For example, use "Tango Dark."

You now have a customized and aesthetically pleasing terminal!
