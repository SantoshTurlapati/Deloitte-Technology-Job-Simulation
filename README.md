# Telemetry Data Format Converter

## Overview

This project converts telemetry data from two different JSON input formats into a single unified JSON format. It ensures that telemetry information from multiple sources is standardized for consistent processing and analysis.

## Features

* Reads telemetry data from JSON files.
* Supports two different input formats.
* Automatically detects the input format.
* Converts ISO 8601 timestamps to milliseconds since the Unix epoch.
* Standardizes device information and telemetry data.
* Validates the output using Python unit tests.

## Project Structure

```
.
├── data-1.json
├── data-2.json
├── data-result.json
├── main.py
└── README.md
```

## Requirements

* Python 3.x

No additional libraries are required. The project uses only Python's standard libraries:

* json
* datetime
* unittest

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/telemetry-data-converter.git
```

2. Navigate to the project directory:

```bash
cd telemetry-data-converter
```

3. Run the project:

```bash
python main.py
```

## Expected Output

If all conversions are implemented correctly, the unit tests will pass:

```
...
----------------------------------------------------------------------
Ran 3 tests in 0.00s

OK
```

## Technologies Used

* Python 3
* JSON
* datetime
* unittest

## Author

Santosh Turlapati
By using
https://cdn.theforage.com/vinternships/companyassets/9PBTqmSxAf6zZTseP/hi756CWPD8rqxCQ8e/1771861490135/data-result.json
https://cdn.theforage.com/vinternships/companyassets/9PBTqmSxAf6zZTseP/hi756CWPD8rqxCQ8e/1771861434240/data-1.json
https://cdn.theforage.com/vinternships/companyassets/9PBTqmSxAf6zZTseP/hi756CWPD8rqxCQ8e/1771861461722/data-2.json
https://cdn.theforage.com/vinternships/companyassets/9PBTqmSxAf6zZTseP/hi756CWPD8rqxCQ8e/1771861515912/main.py

##app
LINK: https://code-linker--sumsantosh91.replit.app/
