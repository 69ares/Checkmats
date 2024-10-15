# Checkmats

Checkmats is a powerful tool designed for Fortnite players to monitor their building materials during intense fights. When you're too focused on the action to check your material count, Checkmats has got your back!

<div style="text-align: center;">
  <img src="https://github.com/69ares/Checkmats/raw/main/img/checkmats.png" alt="Alt text" width="400"/>
</div>

## Features

- **Real-time Material Monitoring**: Continuously scans a selected area of your screen to track your building material count.
- **Audio Alerts**: Provides audio cues when your materials are running low, allowing you to focus on the fight without constantly checking your inventory.
- **Customizable Scan Area**: Easily select the area of your screen where your material count is displayed.
- **Adjustable Scan Interval**: Set how frequently the application checks your material count.
- **CPU/GPU Toggle**: Choose between CPU and GPU processing for optimal performance on your system.
- **Hotkey Support**: Set a custom hotkey to pause/resume the monitoring without alt-tabbing out of your game.
- **Multi-language Support**: Available in English and Italian.

## How It Works

1. **Select Scan Area**: Use the "Select Area" button to choose the part of your screen where your material count is displayed in Fortnite.
2. **Set Scan Interval**: Adjust how often Checkmats should check your material count (in milliseconds).
3. **Start Monitoring**: Click "Start" to begin monitoring your materials.
4. **Audio Alerts**: Checkmats will play different audio cues based on your material count:
   - 500+ materials: No audio (you're well-stocked!)
   - 400-499 materials: First warning
   - 300-399 materials: Second warning
   - 200-299 materials: Third warning
   - 100-199 materials: Fourth warning
   - 0-99 materials: Final warning (time to disengage or farm!)

## Installation

1. Download the latest release from the [Releases](https://github.com/TryAres/Checkmats/releases) page.
2. Extract the ZIP file to your desired location.
3. Run `Checkmats.exe` to start the application.

## Usage

1. Launch Fortnite and ensure it's running in Windowed Fullscreen mode.
2. Start Checkmats and select your preferred language.
3. Use the "Select Area" button to choose the part of your screen where your material count is displayed in Fortnite.
4. (Optional) Adjust the scan interval and set a custom hotkey.
5. Click "Start" to begin monitoring.
6. Play Fortnite as usual - Checkmats will alert you when your materials are running low!

## System Requirements

- Windows 10 or later
- Python 3.7+ (if running from source)
- GPU with CUDA support (optional, for faster processing)

## Contributing

We welcome contributions to Checkmats! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request on our [GitHub repository](https://github.com/TryAres/Checkmats).

## License

Checkmats is released under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- EasyOCR for optical character recognition
- CustomTkinter for the user interface
- PyAutoGUI for screen capture functionality
- Pygame for audio playback

## Disclaimer

Checkmats is an external tool designed to enhance the Fortnite gaming experience. It does not modify game files or interact directly with the game in any way. However, please use at your own risk and ensure you comply with Fortnite's terms of service.
