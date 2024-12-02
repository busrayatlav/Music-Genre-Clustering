# Clustering Music Genres with Machine Learning

This project utilizes machine learning techniques to cluster music tracks based on their audio features, facilitating the identification of similar music genres.

## Table of Contents

* **Introduction**
* **Requirements**
* **Installation**
* **Usage**
* **Project Structure**
* **Results**
* **Contributing**
* **License**
  
## Introduction
The objective of this project is to apply clustering algorithms to a dataset of music tracks, enabling the grouping of songs with similar audio characteristics. This approach can be beneficial for music recommendation systems and genre analysis.

## Requirements

1. Ensure the following Python libraries are installed:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
  
2. Install the required libraries using pip:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Installation
1. Clone the repository:
```
git clone https://github.com/yourusername/your-repo-name.git
```

2. Navigate to the project directory:
```
cd your-repo-name
```

3. Install the dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Place the dataset **(Spotify-2000.csv)** into the data directory.

2. Run the main script to perform clustering:
```
python main.py
```

## Project Structure

The project is organized as follows:

├── data

│   └── Spotify-2000.csv   # Dataset file

├── notebooks

│   └── clustering.ipynb   # Jupyter notebook with clustering analysis

├── src

│   ├── data_preprocessing.py   # Data preprocessing functions

│   ├── clustering.py           # Clustering algorithms

│   └── visualization.py        # Visualization functions

├── README.md

└── requirements.txt


## Results
The clustering analysis groups music tracks into clusters based on their audio features. Visualizations of the clusters are provided in the notebooks/clustering.ipynb file.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License.
