# CLI Weather App 🌦️

A simple and efficient command-line application that provides current weather information for any location. Built with Go, this tool fetches real-time weather data using a public weather API and displays it directly in your terminal.

## Features

- 🌍 **Global Coverage**: Get weather information for any city around the world.
- 🌡️ **Current Conditions**: Displays temperature, weather condition, humidity, and more.
- ⚡ **Fast and Lightweight**: Minimal dependencies and quick responses.
- 💻 **Cross-Platform**: Works on Windows, macOS, and Linux.

## ScreenShot

![App Screenshot](https://github.com/YashSaini99/Weather_App/blob/main/Screenshot.png)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YashSaini99/Weather_App.git
   cd Weather_App
   ```

2. **Build the application**:

   Make sure you have [Go installed](https://golang.org/doc/install) on your system. Then, run:

   ```bash
   go build -o weather
   ```

3. **Install the binary (optional)**:

   If you want to use the app globally, you can move the binary to a directory in your `PATH`:

   ```bash
   mv weather /usr/local/bin/
   ```

## Usage

To get the current weather for a specific city, use the following command:

```bash
./weather "CityName"
```

### Example:

```bash
./weather "New-York"
```

This command will output:

```bash
New York, Clear: 22°C, Humidity: 56%, Wind: 10 km/h
```

## Dependencies

- [github.com/fatih/color](https://github.com/fatih/color) - For colorful terminal output.
- [Weather API Provider](https://www.weatherapi.com/) - For fetching real-time weather data.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/YashSaini99/Weather_App/blob/main/LICENSE) file for details.
