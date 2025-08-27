<div align="center">
  <img src="Assets/tb.png" alt="TwistedBrain Logo" width="200">
</div>

# TwistedBrain Demo Web

A simple OpenFL Haxe demo application for web browsers showcasing TwistedBrain graphics.

## Features

- Interactive logo display with click-to-cycle functionality
- Uses TwistedBrain logo assets (tb.png, tb_2.png, tb_3.png, tb_4.png, tb_5.png)
- Clean, simple UI with welcome text and instructions
- Built specifically for HTML5/web target

## Project Structure

```
TwistedBrainDemoWeb/
├── project.xml              # OpenFL project configuration
├── Source/
│   └── TwistedBrainDemoMain.hx  # Main application class
├── Assets/
│   ├── tb.png               # TwistedBrain logo variants
│   ├── tb_2.png
│   ├── tb_3.png
│   ├── tb_4.png
│   └── tb_5.png
└── Export/
    └── html5/
        └── bin/
            ├── index.html       # Web application entry point
            ├── TwistedBrainDemo.js  # Compiled JavaScript
            └── assets/          # Embedded assets
```

## Requirements

- Haxe 4.3.7+
- OpenFL 9.4.1+
- Lime 8.2.2+
- Modern web browser with HTML5 support

## Building

1. Navigate to the project directory:
   ```bash
   cd TwistedBrainDemoWeb
   ```

2. Build for HTML5:
   ```bash
   haxelib run openfl build html5
   ```

3. Serve the application locally:
   ```bash
   cd Export/html5/bin
   python3 -m http.server 8000
   ```

4. Open in browser:
   ```
   http://localhost:8000
   ```

## Usage

- The application displays a welcome message and the first TwistedBrain logo
- Click anywhere on the screen to cycle through the different logo variants
- The application window is 800x600 pixels with a black background

## Development Notes

- Main class: `TwistedBrainDemoMain`
- Package: `com.twistedbrain.demo`
- Target FPS: 60
- Hardware acceleration enabled
- VSync enabled for smooth rendering

## Assets

All logo assets are sourced from the TB-graphics collection and are automatically embedded in the application during build.

---

<div align="center">
  <em>Made in a AI:Human DevOps cooperation process</em>
</div>