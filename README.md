Here is a `README.md` file for your project:

````markdown
# Currency Reporter

This project fetches currency quotations using the API of NBP, saves filtered data in CSV files, displays basic statistics, and downloads data daily at 12:00 PM.

## Requirements

- Python 3.x
- `requests` library
- `schedule` library

## Installation

1. Clone the repository:
    ```sh
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

Run the main script:
```sh
python main.py
```

## Features

- Fetches quotes for the last 60 days for selected currency pairs.
- Allows user to select specific currency pairs for analysis.
- Saves all fetched data and selected data into CSV files.
- Displays basic statistics (average, median, minimum, maximum) for selected currency pairs.
- Automatically fetches and saves data daily at 12:00 PM.

## Available Currency Pairs

- EUR/PLN
- USD/PLN
- CHF/PLN
- EUR/USD
- CHF/USD

## License

This project is licensed under the MIT License.
````