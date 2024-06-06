
# Exercise Prediction Using Machine Learning

## Project Description
This project aims to develop a machine learning model that can detect specific exercises performed by a person in a video. The exercises include 'Elbow plank,' 'High knees,' 'Squad,' 'Punches,' 'Leg Curls,' 'Superman,' and 'Chest Squeezes.' The model utilizes Python and various machine learning libraries to achieve accurate predictions.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: numpy, pandas, scikit-learn, matplotlib, tensorflow, keras, cv2 (OpenCV), etc.

## Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/AyhanEmirhanAkgun/ExercisePrediction.git
   cd ExercisePrediction
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required libraries:**
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. **Open the Jupyter Notebook:**
   ```sh
   jupyter notebook ExercisePrediction.ipynb
   ```

2. **Run the cells in the notebook to train and test the model.**

## Project Structure
```
ExercisePrediction/
├── data/
│   ├── train/
│   ├── test/
│   └── ...
├── models/
│   └── model.h5
├── ExercisePrediction.ipynb
├── requirements.txt
└── README.md
```

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
