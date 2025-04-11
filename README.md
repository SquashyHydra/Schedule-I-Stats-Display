# Schedule I Stats Display

Schedule I Stats Display is a Python-based application that displays save game statistics for the game "Schedule I". It uses PyWebView for the GUI and integrates with the Steam API to fetch account and game-related data.

## Features

- Fetch and display save game statistics.
- Integrates with the Steam API to retrieve account and game information.
- Interactive GUI built with PyWebView.
- Supports multiple Steam accounts and save folders.

## Requirements

The following Python packages are required to run the application:
- `requests`
- `pywebview`
- `QtPy`
- `cefpython3`
- `nuitka`
- `wheel`
- `setuptools`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SquashyHydra/Schedule-I-Stats-Display.git
   cd Schedule-I-Stats-Display
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your Steam API key:
   - Obtain your Steam API key from [Steam API Key](https://steamcommunity.com/dev/apikey).
   - Enter the key when prompted by the application.

## Usage

1. Run the application:
   ```bash
   python app.py
   ```

2. Follow the on-screen instructions to:
   - Select a Steam account.
   - Choose a save folder.
   - View detailed game statistics.

## Development

### File Structure

- `app.py`: Main entry point for the application.
- `Save.py`: Handles save game data fetching and processing.
- `Steam.py`: Integrates with the Steam API.
- `frontend/`: Contains HTML, CSS, and JavaScript files for the GUI.

### Frontend Files

- `accounts.html`: Displays Steam accounts.
- `loading.html`: Allows users to select save folders.
- `stats.html`: Displays detailed save game statistics.
- `style.css`: Styles for the frontend.
- `scripts.js`, `loading.js`, `stats.js`: JavaScript files for interactivity.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
