# Weather App GUI

## Description
The **Weather App** is a Java-based application that provides users with real-time weather information for a specified location. It fetches weather data from an external API and displays it through a graphical user interface (GUI). Users can enter a location, and the app retrieves and presents essential weather details, including temperature, weather conditions, humidity, and wind speed.


![image](https://github.com/user-attachments/assets/c2a974da-3e47-4a55-ac13-32d4f861d706) 


## Features
- Real-time weather data for specified locations.
- User-friendly graphical interface.
- Dynamic updates based on user input.
- Displays temperature, humidity, and wind speed.

## OOP Concepts Used
- **Encapsulation**: Classes encapsulate functionality and data.
- **Inheritance**: Classes inherit from base classes for code reuse.
- **Polymorphism**: Methods can be overridden for dynamic behavior.

## Technologies and Libraries Used
- **Language**: Java 18
- **Key Libraries and Packages**:
  - **JSON Simple**: For parsing and reading JSON data from the weather API.
  - **HTTPURLConnection**: For making HTTP requests to fetch weather data.
  - **Swing**: For creating the graphical user interface (GUI).
  - **ImageIO**: For loading images within the GUI.
  - **LocalDateTime**: For managing and formatting date and time information.

## Class Summaries
### 1. AppLauncher
Serves as the entry point for the Weather App, initializing the GUI and displaying the main window.

### 2. WeatherAppGui
Represents the GUI of the Weather App, displaying weather information for the specified location.

### 3. WeatherApp
Contains the backend logic for fetching weather data from an external API and managing API requests.
