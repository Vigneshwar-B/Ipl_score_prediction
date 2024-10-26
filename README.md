# IPL First Innings Score Prediction - Deployment
![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)


![IPL Score Prediction](https://via.placeholder.com/800x200.png?text=IPL+First+Innings+Score+Prediction)

## Overview

The IPL First Innings Score Prediction project is a web application built using Flask. It predicts the possible score range for the first innings of an IPL match based on the given inputs. This application leverages a trained Linear Regression model to provide score predictions in real-time.

 ![GIF](readme_resources/ipl-first-innings-score-web-app.gif)

## Features

- **Real-Time Predictions:** Enter match details to get an instant score range prediction.
- **User-Friendly Interface:** Designed with an intuitive interface to enhance the user experience.
- **Versatile Model:** The model considers various factors, including teams, overs, runs, and wickets.
- **Responsive Design:** Works smoothly across different devices.

## Live Demo

🚀 A live demo link will be available soon. Stay tuned!

## Project Structure

```
.
├── readme_resources               # Resources used in README
├── static                         # Static files (CSS, JS, Images)
├── templates                      # HTML templates for Flask
│   ├── index.html                 # Home page with user input form
│   └── result.html                # Result page showing score prediction
├── First Innings Score Prediction - IPL.py  # Notebook for model training
├── app.py                         # Main Flask application file
├── first-innings-score-lr-model.pkl  # Trained Linear Regression model
├── ipl.csv                        # Dataset used for training
├── ipl.ipynb                      # Notebook for data exploration and model creation
├── lr-model.pkl                   # Trained Logistic Regression model (unused)
├── requirements.txt               # Required dependencies
└── README.md                      # Project documentation
```

## Technologies Used

- Python
- Flask
- Scikit-Learn
- Numpy & Pandas
- HTML, CSS, and Bootstrap (for UI)
- Gunicorn (for deployment)

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/IPL-Score-Prediction.git
   cd IPL-Score-Prediction
   ```

2. **Install the Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App:**
   ```bash
   python app.py
   ```
   The app will be running on [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Usage

1. Open the application in your browser.
2. Enter the required inputs such as:
   - Batting Team
   - Bowling Team
   - Current Overs
   - Runs
   - Wickets
   - Runs scored in the last 5 overs
   - Wickets lost in the last 5 overs
3. Click on the **Predict Score** button.
4. The application will display the predicted score range for the first innings.

## Example

![Example Prediction](https://via.placeholder.com/600x300.png?text=Sample+Prediction+Output)

## Model Training

The model was trained using historical IPL data and a Linear Regression model for predicting the score range. You can find the model training and data exploration in the [ipl.ipynb](ipl.ipynb) notebook.

## Requirements

- Flask==1.1.1
- Gunicorn==19.9.0
- Scikit-Learn>=0.18
- Numpy>=1.9.2
- Pandas>=0.19
- Matplotlib>=1.4.3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The IPL data was collected from [source link].
- Special thanks to the contributors and the open-source community.

---

<p align="center">Built with 💙 by Vigneshwar B.</p>
```

This `README.md` file provides a clear project description, usage instructions, and installation details while maintaining an aesthetic layout. Feel free to adjust links, images, or acknowledgments as needed!
