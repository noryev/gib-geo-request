# NASA GIBS Earth Imagery

## Overview
This project utilizes the NASA Global Imagery Browse Services (GIBS) API to fetch satellite imagery of the Earth, with a specific focus on global imagery and detailed imagery of the central United States. The Python code in this repository facilitates the retrieval and processing of these images for various applications such as environmental monitoring, weather tracking, and educational purposes.

## Features
- Fetching full Earth imagery from NASA GIBS.
- Fetching detailed satellite images of the central United States.
- Processing and storing images in user-friendly formats.
- Options to filter images based on various parameters like date, resolution, etc.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.x installed.
- Libraries: `requests`, `PIL` (Pillow), and other dependencies listed in `requirements.txt`.

## Installation
Clone the repository to your local machine:
```
git clone https://github.com/your-username/nasa-gibs-earth-imagery.git
```
Navigate to the project directory and install the required Python packages:
```
cd nasa-gibs-earth-imagery
pip install -r requirements.txt
```

## Usage
The main script can be executed with Python. Command line arguments can be used to specify parameters such as the target region (global or central US) and date of imagery.

Example usage:
```
python get_imagery.py --region global --date 2023-01-01
```

## NASA GIBS API Overview
The NASA GIBS API provides access to different types of Earth imagery from various satellite missions. This project makes use of the API to retrieve images based on the provided parameters.

### API Endpoints
- Global imagery: `https://gibs.earthdata.nasa.gov/path/to/global/imagery`
- Central United States imagery: `https://gibs.earthdata.nasa.gov/path/to/central-us/imagery`

### API Parameters
- `date`: The date of the imagery.
- `format`: The format of the returned imagery (e.g., JPEG, PNG).
- More details can be found in the official [NASA GIBS API documentation](https://gibs.earthdata.nasa.gov/api/).

## Contributing
Contributions to this project are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- NASA GIBS team for the amazing imagery service.
- Contributors who have participated in this project.
