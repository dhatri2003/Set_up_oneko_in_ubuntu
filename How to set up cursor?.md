# oneko

`oneko` is a fun, lightweight program that adds a cat (or dog, or other characters) that chases the mouse cursor around the screen. This README provides installation instructions, usage examples, and some customization tips.

## Installation

To install `oneko` on your Ubuntu system, follow these steps:

1. Open a terminal.
2. Update the package lists:
    ```sh
    sudo apt-get update
    ```
3. Install `oneko`:
    ```sh
    sudo apt-get install oneko
    ```

## Usage

Once installed, you can run `oneko` with different options. Below are some examples:

- To start `oneko` with the default cat character:
    ```sh
    oneko
    ```

- To use the dog character:
    ```sh
    oneko -dog
    ```

- To use the sakura character:
    ```sh
    oneko -sakura
    ```

- To use the tomoyo character:
    ```sh
    oneko -tomoyo
    ```

- To change the background color:
    ```sh
    oneko -bg blue
    ```

- To change the foreground color:
    ```sh
    oneko -fg yellow
    ```

- To set the time interval:
    ```sh
    oneko -time 30000
    ```

You can combine options to customize the appearance and behavior of the character:

```sh
oneko -dog -fg yellow -time 30000
