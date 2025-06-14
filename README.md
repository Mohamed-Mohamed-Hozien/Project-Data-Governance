# Project Data Governance

A data governance and analysis project focused on bike-sharing data, featuring data validation, visualization, and analysis capabilities.

## Project Overview

This project implements data governance practices for bike-sharing data, including:
- Data validation using Pandera schemas
- Geographic data visualization
- Data analysis and processing
- Interactive map visualizations

## Project Structure

- `main.ipynb`: Main Jupyter notebook containing data processing and analysis code
- `Schema.txt` & `Schema_cleaned.txt`: Data validation schemas using Pandera
- `map.html`: Interactive map visualization
- `output.html`: Processed data output
- `member_coordinates.csv` & `casual_coordinates.csv`: Processed coordinate data
- `Phase 0.docx` & `Phase 1&2.docx`: Project documentation and requirements

## Data Schema

The project implements a comprehensive data validation schema that includes:
- Ride identification and type
- Timestamp data (start/end times)
- Station information (names and IDs)
- Geographic coordinates (latitude/longitude)
- User type classification (member/casual)

## Features

- Data validation and quality checks
- Geographic data processing
- Interactive visualizations
- Coordinate mapping and analysis
- User type classification and analysis

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandera
- Data visualization libraries
- Geographic data processing libraries

## Usage

1. Clone the repository
2. Install required dependencies
3. Open `main.ipynb` in Jupyter Notebook
4. Run the cells sequentially to process and analyze the data
5. View the generated visualizations in `map.html`

## Data Validation

The project uses Pandera for data validation, ensuring:
- Data type consistency
- Value range validation
- Required field presence
- Geographic coordinate bounds checking

## Visualization

The project includes interactive visualizations:
- Geographic mapping of bike stations
- User type distribution
- Ride patterns and trends

## License

[Add appropriate license information]

## Contributing

[Add contribution guidelines if applicable]
