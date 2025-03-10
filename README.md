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