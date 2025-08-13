# **Tricade – Fossil Project**

**Tricade** is a command-line collection of classic text-based games, including Rock Paper Scissors, Guess the Number, Hangman, and more. It can be run interactively via a menu or directly from the command line for quick gameplay.

## **Prerequisites**

Ensure the following are installed:

- **Meson Build System** – used for building the project. Installation instructions are available on the [Meson website](https://mesonbuild.com/Getting-meson.html).  
- **C Compiler** – any standard C compiler (e.g., GCC, Clang).  

## **Setting Up Meson Build**

1. **Install Meson**: Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running Tricade**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/tricade.git
    cd tricade
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run Tricade**:

    ```sh
    tricade                  # Launch main menu
    tricade play <game>      # Launch a specific game directly
    tricade list             # List all available games
    tricade help             # Show global help
    tricade help <game>      # Show help for a specific game
    tricade --version        # Show version info
    ```

## **Command Overview**

| Command                  | Description                                       |
|---------------------------|---------------------------------------------------|
| `tricade`                 | Launch the interactive main menu                  |
| `tricade play <game>`     | Play a specific game directly                     |
| `tricade list`            | List all available games                           |
| `tricade help`            | Show global help                                   |
| `tricade help <game>`     | Show help for a specific game                     |
| `tricade --version`       | Show Tricade version information                  |

## **Contributing**

Contributions are welcome! Open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/tricade).

## **Feedback and Support**

For questions, issues, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/tricade/issues).

## **License**

This project is licensed under the [Mozilla Public License](LICENSE).
