# Create Development Environment

## Development Containers (devcontainers)

Development Containers is a specification that allows repositories to introduce a normalized way of interacting with their repository. When using an IDE like Visual Studio Code you are able to install the devcontainers extension and open the repository in a container. The end result is anyone who interacts with the repository should be able to rely on this container specification to facilitate development with confidence that it will work on other machines as long as they have a container technology installed.

## Instructions

### 1. Prequisites
- Install Container Technology (Docker or Podman).
- Install Visual Studio Code.
- Install Dev Containers extension.
- Install RuboCop extension.
- Install Ruby extension.

### 2. Clone Repository
- Run `git clone https://github.com/dependabot/dependabot-core.git` in the directory of your choice.

### 3. Open Dev Container
- Open the newly cloned `dependabot-core` directory in Visual Studio Code.
- Click on the Remote Host icon in the bottom left corner of Visual Studio. It is blue and looks like `><`.
- Choose the `Reopen in Container` option.
- Choose the `core-dev` Dev Container option.
- Visual Studio Code will restart and start opening the repository in a container image.
  - In the bottom right corner of Visual Studio Code it will indicate the container image is being downloaded.
- After the the container image has been downloaded the Explorer window will display 
- Wait for Visual Studio Code to download the container image.
- Upon completion of downloading and setting up the container image you will be able to view the contents of the container development environment in the Explorer window.

### 4. Confirm Dev Container is Functional
- Click the Run and Debug tab on the left.
- Select the Debug Dry Run option.
- Select the NuGet option.
- Provide the repository `https://github.com/dotnet/aspire-samples`.

TODO beyond this point because bug was hit.
