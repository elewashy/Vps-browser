# Vps Browser Installer

This Bash script enables you to quickly install various web browsers using Docker containers. It provides a simple menu interface for selecting the browser you want to install.

## Features

- Installation of multiple web browsers including Chromium, Firefox, Opera, and Mullvad Browser.
- Easy-to-use menu interface for browser selection.
- Docker-based installation ensures easy deployment and isolation.

## Preview

![Vps Browser Installer](https://raw.githubusercontent.com/elewashy/vps-browser/main/Preview.jpg)

## Usage

### Running in Google Cloud Shell

- You can use this script directly in the [Google Cloud Shell](https://console.cloud.google.com/welcome) by running the following command: 

```bash
curl -sLkO https://raw.githubusercontent.com/elewashy/vps-browser/main/vps-browser.sh && bash vps-browser.sh
```
- Follow the on-screen instructions to select and install the desired browser.
- When the download is finished, click on the web preview icon and choose Change port from the menu.
- Type port 3000 and click change and preview.


### Cloning the Repository

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/elewashy/vps-browser.git
    ```

2. Navigate to the cloned directory:

    ```bash
    cd online-browser
    ```

### Running the Script

3. Make the script executable:

    ```bash
    chmod +x online-browser.sh
    ```

4. Run the script:

    ```bash
    ./online-browser.sh
    ```

### Selecting a Browser

5. Follow the on-screen instructions to select and install the desired browser.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/elewashy/online-browser/blob/main/LICENSE) file for details.
