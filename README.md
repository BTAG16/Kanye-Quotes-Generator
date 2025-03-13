# Kanye Quotes Generator

A simple Python application that displays random quotes from Kanye West. The application fetches quotes from a public API and displays them in a GUI built with **Tkinter**.

## Features

- **Random Quotes**: Fetches a random Kanye West quote using the `https://api.kanye.rest` API.
- **GUI Interface**: The application uses **Tkinter** to display quotes in an attractive window with a background image.
- **Button to Fetch New Quotes**: Click the Kanye West image to retrieve a new quote.

## Tech Stack

- **Python 3.x**
- **Tkinter**: For creating the graphical user interface.
- **requests**: To fetch quotes from the Kanye API.

## Setup

### Prerequisites

1. **Install Python 3.x**: Ensure Python 3.x is installed on your system.
2. **Install Dependencies**: Use pip to install the required libraries:
    ```bash
    pip install requests
    ```

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/btag16/kanye-quotes-generator.git
   cd kanye-quotes-generator
   ```

2. Place your **background image** (`background.png`) and **Kanye image** (`kanye.png`) in the project folder.

3. Run the script:
   ```bash
   python kanye_quotes_generator.py
   ```

4. Click the Kanye West image to fetch a random quote and display it on the GUI.

### Notes

- **Customizing Images**: You can change the `background.png` and `kanye.png` to your own images for personalization.
- **API**: The quotes are fetched from the `https://api.kanye.rest` API. If the API is down or unreachable, the program will print an error message.

## License

This project is licensed under the MIT License.

---

Feel free to contribute, suggest improvements, or ask questions by opening an issue in this repository.
