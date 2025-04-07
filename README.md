# thevvibesai

## Offline AI Music Generator App for macOS Apple M1

This is an offline AI music generator app for macOS Apple M1. The app uses tkinter as the UI framework and downloads AI models from Hugging Face on the first launch. The user can choose the directory for the models' path.

## Installation and Running the App

1. Clone the repository:
   ```
   git clone https://github.com/mandaliyavatsal/thevvibesai.git
   cd thevvibesai
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the app:
   ```
   python main.py
   ```

## Building the .app File Using PyInstaller

1. Install PyInstaller:
   ```
   pip install pyinstaller
   ```

2. Build the .app file:
   ```
   pyinstaller thevvibesai.spec
   ```

3. The .app file will be created in the `dist` directory.
