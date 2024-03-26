# Ryne's OhMyPosh Repository

This repository is dedicated to storing various themes for the ohmyposh project. Ohmyposh is a command prompt customization tool for Windows PowerShell and PowerShell Core.

## Installation

To use the themes in this repository, you'll need to have ohmyposh installed on your system. If you haven't installed it yet, follow the instructions in the [ohmyposh documentation](https://ohmyposh.dev/docs/installation) to get started.

## Usage

1. Clone this repository to your local machine:

    ```shell
    git clone https://github.com/ryne/ohmyposh.git
    ```

2. Navigate to the cloned repository:

    ```shell
    cd ohmyposh
    ```

3. Copy the desired theme file(s) to your ohmyposh themes directory. The default themes directory is usually located at `~\Documents\PowerShell\Modules\oh-my-posh\themes`.

4. Open your PowerShell profile file (e.g., `$PROFILE`) and add the following line to set the desired theme:

    ```shell
    Set-Theme <theme-name>
    ```

    Replace `<theme-name>` with the name of the theme file you copied in step 3.

5. Save the profile file and restart your PowerShell session.

## Contributing

If you'd like to contribute to this repository by adding new themes or improving existing ones, feel free to submit a pull request. Please follow the contribution guidelines outlined in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the [MIT License](LICENSE).