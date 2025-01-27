# Installing whisper.cpp

To build and install whisper.cpp system-wide on your macOS system, follow these steps:

1. Configure the build:
```bash
cmake -B build
```

2. Build the project:
```bash
cmake --build build --config Release
```

3. Install the binary and libraries (may require sudo):
```bash
sudo cmake --install build
```

After installation, you can run the whisper-cli command from anywhere on your system:
```bash
whisper-cli -f /path/to/audio.wav
```

The binary will be installed to /usr/local/bin by default.