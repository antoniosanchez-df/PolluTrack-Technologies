
# Air Quality Index (AQI) Calculation Project

This project provides a mechanism to calculate the Air Quality Index (AQI) based on various regional rules. The regions currently supported include Europe and the UK, with placeholder support for the USA and China.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Supported Regions](#supported-regions)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

1. Ensure you have Python 3.x installed.
2. Clone this repository:
    ```
    git clone https://github.com/antoniosanchez-df/PolluTrack-Technologies.git
    ```
3. Install the required packages:
    ```
    pip install pandas numpy geopy countrygroups
    ```

## Usage

1. Import the required classes:
    ```python
    from aqi_calculator import AQICalculator
    ```

2. Initialize the AQI Calculator:
    ```python
    calculator = AQICalculator()
    ```

3. Set your data (either JSON string or DataFrame):
    ```python
    calculator.set_data(your_data)
    ```

4. Calculate the AQI:
    ```python
    result = calculator.calculate_aqi()
    ```

5. `result` will contain the AQI calculations based on the regional rules.

## Supported Regions

- Europe (based on EUROPEAN_UNION countries)
- UK

Placeholder support:
- USA
- China

## Contributing

1. Fork the repository on GitHub.
2. Clone your fork and create a new branch for your feature or fix.
3. Commit your changes and push to your fork.
4. Open a pull request against the main repository.

## License

This project is licensed under the MIT License. See `LICENSE` file for more details.
