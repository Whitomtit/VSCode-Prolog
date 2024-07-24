## Prolog Setup for VSCode

This repository includes a configuration to set up a Prolog development environment using DevContainers in Visual Studio Code (VSCode). This allows you to develop in a consistent environment without the hassle of manually setting up dependencies on your local machine.

### Prerequisites

1. **Visual Studio Code**: Make sure you have the latest version of VSCode installed. You can download it from [here](https://code.visualstudio.com/).
2. **Docker**: Ensure Docker is installed and running on your machine. You can find the installation guide [here](https://docs.docker.com/get-docker/).
3. **Dev Containers Extension**: Install the "Dev Containers" extension in VSCode. You can find it [here](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).

### Setting Up the DevContainer

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Whitomtit/VSCode-Prolog.git
    cd VSCode-Prolog
    ```

2. **Open the Repository in VSCode**:
    Open VSCode and select `File > Open Folder...`, then choose the cloned repository folder.

3. **Reopen in Container**:
    - Once the repository is open in VSCode, you should see a prompt at the bottom right corner asking if you want to reopen the folder in a container. Click on `Reopen in Container`.
    - If you don't see the prompt, you can manually reopen in the container by pressing `F1`, then typing and selecting `Dev Containers: Reopen in Container`.

### Running Prolog Files

This repository is configured to use SWI-Prolog. You can run Prolog files by pressing F1, the typing and selecting `Prolog: load document`.

### Common Commands

- **Start the Container**: Automatically handled when you open the folder in the container.
- **Access the Terminal**: You can open a terminal inside the container by pressing ``Ctrl+` `` (backtick) or selecting `Terminal > New Terminal`.

### Troubleshooting

- **Container Fails to Start**: Ensure Docker is running and you have the latest version of VSCode and the Dev Containers extension.

### Additional Resources

- [VSCode Dev Containers Documentation](https://code.visualstudio.com/docs/remote/containers)
- [Docker Documentation](https://docs.docker.com/)
- [SWI-Prolog Documentation](https://www.swi-prolog.org/)
