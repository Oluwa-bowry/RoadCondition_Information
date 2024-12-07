# Add a Line to a Map using GeoJSON Source

This project demonstrates how to visualize road conditions using Mapbox GL JS by adding a line to a map based on a GeoJSON source. The application fetches data from an API and dynamically updates the map to reflect real-time road conditions.

## Features

- Visualize road conditions with color-coded indicators:
  - **Red**: High presence of potholes
  - **Blue**: Speed bumps
  - **Green**: Smooth road conditions
  - **Yellow**: Unlabeled road conditions
- Cache GeoJSON data locally to improve performance and offline usage.
- Refresh data manually using a button.
- Mark key locations like the starting point and destination.

## Technology Stack

- **HTML/CSS/JavaScript**: For front-end development.
- **Mapbox GL JS**: For interactive map rendering.
- **JSONBin.io**: For storing and fetching GeoJSON data.

## Prerequisites

- A Mapbox access token. Sign up at [Mapbox](https://www.mapbox.com/) to get your access token.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/road-condition-map.git
   cd road-condition-map
   ```
2. Replace the placeholder access token in the script tag with your Mapbox access token:
   ```javascript
   mapboxgl.accessToken = 'your-mapbox-access-token';
   ```
3. Ensure you have access to a valid JSONBin API endpoint.

## Usage

1. Open `index.html` in your preferred browser.
2. The map will automatically display road conditions based on cached or API data.
3. Use the **Refresh Data** button to load the latest road condition data.

## Project Structure

- **index.html**: Contains the main HTML structure and JavaScript logic.
- **styles**: CSS for responsive and aesthetic styling.

## API Integration

The project fetches GeoJSON data from a JSONBin.io endpoint. To configure:

- Update the `url` variable with your JSONBin API endpoint.
- Set your JSONBin master key in the request headers.

## Local Storage

- Cached GeoJSON data is saved to local storage for improved performance and offline functionality.

## Key Features of the Map

1. **Markers**: Indicates the starting point and destination.
2. **Color-coded Lines**: Display road conditions based on the `road_label` property of the GeoJSON data.

## Contribution

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add feature-name'
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [your-email@example.com](mailto\:your-email@example.com)
- **GitHub**: [your-usern](https://github.com/your-username)
