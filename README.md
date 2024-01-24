# Archive Large Files Script

This script is designed to automate the process of archiving files larger than 20MB in a specified directory. It is especially useful for managing disk space and organizing large files efficiently.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features

- Automatically identifies and archives files larger than 20MB.
- Configurable depth for file search within the directory.
- Customizable target directory for archiving.
- Timestamped logging for archiving activities.

## Prerequisites

- Bash: The script is written in Bash and requires a Bash-compatible shell.
- Linux Environment: The script is designed to run on Linux systems.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Shubham-Sharma-sk/Shell_script_project
    ```

2. Navigate to the project directory:

    ```bash
    cd Shell_script_project
    ```

## Usage

1. Ensure that the script has execution permissions:

    ```bash
    chmod +x archive_project.sh
    ```

2. Run the script:

    ```bash
    ./archive_project.sh
    ```

## Configuration

You can configure the script by modifying the variables in the script:

- `BASE`: The base directory to start the search for large files.
- `DEPTH`: The depth of the directory tree to search.
- `RUN`: Set to `0` to enable archiving, or `1` to disable (dry-run mode).

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request. Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
