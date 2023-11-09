# Django REST Api
[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/gadc1996/django-api)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
## Setting Up

### Prerequisites

Before you begin, make sure you have the following:

- [Docker](https://www.docker.com/) installed on your system.
- [Visual Studio Code](https://code.visualstudio.com/) installed.

## Installing Dev Containers

Follow these steps to install Dev Containers:

1. Open Visual Studio Code.

2. Install the [Visual Studio Code Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) from the VS Code extensions store.

3. Restart Visual Studio Code if prompted.

## Basic Usage of Dev Containers

To use Dev Containers with your project:

1. Open your project in Visual Studio Code.

2. Select 'Reopen in container' from the dialog that appears if the project is already configured with Dev Containers.
   ![image](https://github.com/gadc1996/django-api/assets/67934500/1e04731b-d889-479c-8f2d-25b593f5e43b)

   Alternatively, you can open the command palette (Ctrl + Shift + P) and select "Dev Containers: Rebuild and Reopen in Container."
   ![image](https://github.com/gadc1996/django-api/assets/67934500/9350b990-856e-4a16-9cce-55c51ea69d1a)

3. Once the Dev Container configuration is complete, an instance of VS Code will be generated with all the necessary tools for your project. You can confirm this because the title bar will display "Dev Container" followed by the name of your project.
   ![image](https://github.com/gadc1996/django-api/assets/67934500/0bb9f5ca-f6a4-4cd1-869c-77283c489d73)

   Enjoy the flexibility and consistency that Dev Containers offer for your software development!

## Cli
The project includes a cli utility, powered by [Click](https://click.palletsprojects.com/en/8.1.x/)to manage development common work flows, for more information on available commands use:

```shell
cli command <command_name>
```

### Extending cli
You can use command:
```shell
cli command <command_name>
```
To generate a new cli using the project template, new commands are registered automatically,check [cli.py](./cli.py) for more information.
