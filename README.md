# Weather Tracker

A simple weather-tracking application that fetches real-time weather data using Python and an external API.

## Features

- Fetches real-time weather data based on user input.
- Displays information such as temperature, humidity, and general weather conditions.
- Supports multiple cities and locations for live updates.

## Technologies Used

- Python
- API integration (e.g., OpenWeatherMap API)

## Installation and Setup

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/weather-tracker.git
    cd weather-tracker
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Add your API key**:

    - Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).
    - Create a `config.py` file in the root directory and add your API key:
    
    ```python
    # config.py
    API_KEY = 'your_api_key_here'
    ```

5. **Run the application**:

    ```bash
    python weather_tracker.py
    ```

## Usage

1. **Enter a city or location** when prompted to get the current weather conditions.

2. The application will display:
   - Temperature
   - Humidity
   - General weather description

## Contributing

Feel free to submit issues or contribute to the project via pull requests.

## License

This project is licensed under the MIT License.
