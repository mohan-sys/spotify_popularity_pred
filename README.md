# Song Popularity Prediction Model

This repository contains code for building a machine learning model to predict the popularity of songs using the provided dataset. The dataset used for this task is drawn from [Spotify Past Decades Songs (50s-10s)](https://www.kaggle.com/cnic92/spotify-past-decades-songs-50s10s). Please note that the original dataset has been slightly modified; the first column "Number" has been renamed as "Id".

## Dataset Information

The dataset contains information about various attributes of songs across different decades. There are 13 attributes (excluding "Id" and "popularity") that can be used for building the prediction model. It's important to note that there are some missing values in the dataset, and the year attribute may not always be coherent due to factors like re-releases.

## Objective

The goal of this project is to develop a machine learning model that accurately predicts the popularity of songs. Since popularity is represented as an integer value, this task is treated as a regression problem. The performance of the model will be evaluated based on the Root Mean Squared Error (RMSE) metric.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your_username/song-popularity-prediction.git
```

2. Download the training data from the competition page mentioned above.

3. Install the required dependencies using:

```bash
pip install -r requirements.txt
```

4. Explore, understand, and clean the data. Utilize as many or as few of the available attributes as you see fit for building your model.

5. Train and evaluate your machine learning model using appropriate techniques.

## File Descriptions

- `data/`: This directory contains the dataset file(s).
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, model development, and evaluation.
- `models/`: Trained machine learning models.
- `src/`: Source code files for data preprocessing, model training, and evaluation.
- `requirements.txt`: List of Python dependencies required for this project.

## Usage

After setting up the project and preprocessing the data, you can train your model using the provided scripts or Jupyter notebooks. Once the model is trained, you can use it to make predictions on new data.

## Evaluation

The performance of the model will be evaluated based on the RMSE metric. Aim to minimize the RMSE to build an effective prediction model.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Dataset provided by [Spotify Past Decades Songs (50s-10s)](https://www.kaggle.com/cnic92/spotify-past-decades-songs-50s10s).
- This project is part of a class assignment.

Feel free to customize this README as needed for your project. Happy modeling! 🎵🎶
