#Everyone can use English

## Table of contents

- [Introduction](./book/README.md)
- [Chapter 1: Starting Point](./book/chapter1.md)
- [Chapter 2: Speaking](./book/chapter2.md)
- [Chapter 3: Voice](./book/chapter3.md)
- [Chapter 4: Reading](./book/chapter4.md)
- [Chapter 5: Dictionary](./book/chapter5.md)
- [Chapter 6: Grammar](./book/chapter6.md)
- [Chapter 7: Intensive Reading](./book/chapter7.md)
- [Chapter 8: Advice](./book/chapter8.md)
- [Postscript](./book/end.md)

## Application

- [Enjoy App](./enjoy/README.md)

## * Developer

### Local startup

```bash
yarn install
yarn start:enjoy
```

### Compile

```bash
yarn make:enjoy
```

## * Ordinary novice users

Method 1: This is the **most direct and simple method** to go to the [releases page](https://github.com/xiaolai/everyone-can-use-english/tags) to download the corresponding installation file.

Method 2: If you want to **try the updated version** at any time, please follow the steps.

### MacOS users

1. Open the command line tool Terminal
2. Install Homebrew (please refer to this article: "[Start from Terminal...](https://github.com/xiaolai/apple-computer-literacy/blob/main/start-from-terminal.md)")
3. Install yarn:

    ```bash
    brew install yarn
    ```
4. Clone this repository locally, then install and start:

    ```bash
    cd ~
    mkdir github
    cdgithub
    git clone https://github.com/xiaolai/everyone-can-use-english
    cd everyone-can-use-english
    yarn install
    yarn start:enjoy
    ```

### Windows users

System requirements: Windows 10 22H2 or above, [Windows PowerShell 5.1](https://aka.ms/wmf5download) or above, and a normal Internet connection.

1. Move the mouse to the "Windows logo" on the taskbar, right-click and select "PowerShell"

    > tips 1: On the latest Windows 11, you can’t see the “PowerShell” option, only “Terminal”
    >
    > tips 2: Do not run PowerShell with administrator privileges, otherwise Scoop installation will fail.
    >
2. In the pop-up PowerShell window, execute the following commands in order to install Scoop:

    ```powershell
    # Set PowerShell execution policy
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
    # Download the installation script
    irm get.scoop.sh -outfile 'install.ps1'
    # Execute installation, the --ScoopDir parameter specifies the Scoop installation path
    .\install.ps1 -ScoopDir 'C:\Scoop'
    ```

    If the following error occurs:

    > `<span style="color:red">`irm: Unable to resolve the remote name: 'raw.githubusercontent.com'
    >

    It means there is a problem with your **network connection**. Please research and solve it yourself:
3. Install Nodejs, yarn and other dependent environments:

    ```powershell
    scoop install nodejs
    scoop install git
    npm install yarn -D
    ```
4. Clone this repository locally and install Enjoy APP:

    ```powershell
    cd ~
    mkdir github
    cdgithub
    git clone https://github.com/xiaolai/everyone-can-use-english
    cd everyone-can-use-english
    cd enjoy
    yarn install
    yarn start:enjoy
    ```

    Words like `Completed in XXXXXXXXXX` appear, indicating that the installation is successful!
5. Run Enjoy APP and execute the following commands in the terminal:

    ```powershell
    yarn start:enjoy
    ```

##UpdateEnjoy

Update and use the latest version of Enjoy:

1. Pull the latest contents of the warehouse to the local computer and execute it in the command line tool:

    ```bash
    git pull
    ```
    The result is shown as:

    ```shell
    Already up to date.
    ```
2. Run Enjoy APP:

    ```shell
    yarn start:enjoy
    ```
