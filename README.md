# Escavador Cases

This repository contains a Python script to fetch legal processes for a company using the Escavador API and save the details into a CSV file.

## Prerequisites

- Python 3.x
- `csv` module (standard library)
- `escavador` package (install via `pip install escavador`)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/escavador-processes.git
    cd escavador-processes
    ```

2. Install the required package:

    ```bash
    pip install escavador
    ```

3. Set your Escavador API key in the script (`ESCAVADOR_API_KEY` variable).

## Usage

Run the script to fetch processes and save them into `processes.csv`:

```bash
python processes.py

