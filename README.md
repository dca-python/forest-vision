# ForestVision 🛰️

ForestVision is a web-based tool designed to analyze deforestation over a specified period using satellite imagery. This application allows users to select geographic coordinates and a time frame to visualize changes in forest cover and quantify the extent of deforestation.

ForestVision was created by a team of four as the final project of Le Wagon's Data Science & AI Bootcamp. 
This repo is a slightly restructured copy of the two repositories we used to separately develop the [frontend](https://github.com/vikfalk/deforestation_frontend) and [backend](https://github.com/vikfalk/deforestation_backend) of the web app – merged together for display purposes.

![Mock-up_1x](https://github.com/vikfalk/deforestation_frontend/assets/165885171/483ef44f-ded0-4660-90da-8ed36125fd69)

## Features

- **Geographic Selection**: Select any location globally using latitude and longitude inputs.
- **Time Frame Specification**: Define the start and end dates to analyze deforestation within that period.
- **Image Processing**: Retrieve and process satellite images to identify and visualize forest cover changes.
- **Interactive Map**: Display the selected area on an interactive map with an overlay indicating the deforested area.
- **Deforestation Metrics**: Calculate and display key metrics, including the percentage of forest cover loss, total deforested area in hectares, and annual CO2 loss due to deforestation.

## Try ForestVision Online

You can try ForestVision without installing anything by visiting our web app at [ForestVision Web App](https://forest-vision-sjdauzt4idxdndzoewe56t.streamlit.app/). Explore deforestation trends and visualize forest cover changes directly in your browser 🌳

### Usage

1. **Select Location and Time Frame**:
    - **Coordinates**: Input the latitude and longitude for the area of interest.
    - **Time Frame**: Choose the start and end dates for the analysis.

2. **View and Analyze Results**:
    - **View on Map**: Click the "View on map" button to display the selected area on the map.
    - **Calculate**: Click the "Calculate" button to start the image retrieval and processing. The results will include satellite images, forest overlays, and deforestation metrics.

## Acknowledgements

This project utilizes various open-source libraries and APIs for satellite imagery and image processing. Special thanks to the developers and contributors of these tools.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
