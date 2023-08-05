# Person Of Interest Finder



## Overview

Person Of Interest Finder is a Python module designed to facilitate the search for persons of interest within large sets of images and videos. The project leverages the power of PySpark for big data processing and the Deepface library for efficient image and video analysis. With this tool, you can quickly and accurately identify individuals of interest from vast amounts of visual data.

## Key Features

- **Scalable and Distributed Processing:** The project utilizes PySpark to handle large datasets, enabling scalable and distributed processing across multiple nodes.

- **Deepface Integration:** By integrating Deepface, Person Of Interest Finder can conduct accurate and efficient face recognition in images and videos.

- **Flexible Configuration:** The module provides various configuration options to customize the search criteria, face recognition model, confidence thresholds, and parallel processing settings.

## How it Works

1. **Data Preparation:** Before using Person Of Interest Finder, you need to gather a substantial dataset containing images and videos containing the persons of interest you want to search for.

2. **PySpark for Big Data Processing:** Person Of Interest Finder employs PySpark to process the large dataset in parallel. This enables efficient handling of big data, reducing processing time and improving performance.

3. **Face Recognition with Deepface:** The module leverages the Deepface library, which uses state-of-the-art deep learning models to perform accurate face recognition. This ensures reliable identification of the persons of interest within the visual data.

4. **Search Criteria:** You can set up the search criteria by providing the image of the person you want to search for and specifying a confidence threshold to filter the results.

5. **Search Results:** After processing the dataset, Person Of Interest Finder returns a list of search results, including the matched images and in case of videos it will return a list of timestamps where that particular parson was seen. 

## Examples

To help you get started, you check the jupyter notebook and change the dataset directory accordingly. 

## Contributing

We welcome contributions from the community to improve and extend Person Of Interest Finder. If you encounter any issues or have ideas for enhancements, please feel free to open an issue or submit a pull request.

For major changes, please open an issue first to discuss the proposed changes and their impact.
