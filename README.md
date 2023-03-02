# LaTeX Configuration File

Create latex configuration in command line.

## Setup

1. Clone the repository to your machine and `cd` to directory.

    ```sh
    git clone https://github.com/steguiosaur/latex-file.git && cd ./latex-file
    ```

2. Execute `texconfig-installer`.

    ```sh
    ./texconfig-installer
    ```

    > If `textconfig-installer` is not executable.

    ```sh
    chmod +x textconfig-installer && ./texconfig-installer
    ```

## Usage

Input the command `texconf <filename.tex>` to generate the file.

```sh
texconf "filename.tex"
```

To update the configuration file, run the command:

```sh
cp ./default.tex ~/.config/texconf/default.tex
```
