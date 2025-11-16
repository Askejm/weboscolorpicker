# weboscolorpicker

Displays solid contrasts for LG WebOS TVs. Making this so I can check my burn in and I don't have to get up and hit the light switch if I need some light real quick.

## Features

- Display any shade of gray from 0% (black) to 100% (white)
- Precise 1% increments for fine-tuning
- Preset buttons for quick access (0%, 25%, 50%, 75%, 100%)
- Hide/unhide UI for clean fullscreen display
- Full LG webOS remote control support
- Keyboard controls for testing

## Installation

1. Install webOS CLI tools:
   ```bash
   npm install -g @webos-tools/cli
   ```

2. Package the app:
   ```bash
   ares-package .
   ```

3. Install on your LG TV:
   ```bash
   ares-install com.webos.colorpicker_1.0.0_all.ipk -d <your-tv-name>
   ```

4. Launch the app:
   ```bash
   ares-launch com.webos.colorpicker -d <your-tv-name>
   ```

## Controls

### Remote Control
- **Up/Down arrows**: Adjust gray level by 1%
- **Channel Up/Down**: Adjust by 10%
- **OK/Enter button**: Toggle UI visibility
- **Preset buttons**: Jump to specific gray levels

### Keyboard (for testing)
- **Arrow Up/Down**: Adjust by 1%
- **Page Up/Down**: Adjust by 10%
- **Space or H**: Toggle UI visibility

## Use Cases

- Burn-in testing and detection
- Quick room lighting without getting up
- Screen uniformity testing
- Calibration reference
- Ambient lighting
