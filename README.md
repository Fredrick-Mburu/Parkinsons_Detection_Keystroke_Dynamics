# Parkinson's Disease Detection Through Keystroke Dynamics

## Project Description
This machine learning project aims to detect Parkinson's Disease (PD) by analyzing keystroke dynamics. It's part of an initiative to explore non-invasive and accessible diagnostic tools for neurological conditions.

## Overview
We use a Random Forest classifier to distinguish between individuals with and without PD based on their typing patterns. The data encompasses keystroke timing information from typing sessions, labeled according to the presence of PD.

## How It Works
The analysis hinges on the hypothesis that PD affects motor control, which in turn impacts typing behavior. By examining keystroke timing and applying machine learning models, we can detect deviations from typical typing patterns indicative of PD.

## Table of Contents
- [Getting Started](#getting-started)
- [Contents](#contents)
- [Results](#results)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)
- [Contact](#contact)

## Getting Started
1. Clone the repository:
   ```bash
   https://github.com/Fredrick-Mburu/Parkinsons_Detection_Keystroke_Dynamics/tree/main

##  Install the necessary Python libraries:

pip install -r requirements.txt

## Run the Jupyter Notebook for a detailed walkthrough:

    jupyter notebook Parkinsons_Detection_Keystroke_Dynamics.ipynb

## Contents

    notebooks/: Contains Jupyter notebooks with detailed analysis and model development.
    data/: Dataset used for the model (https://www.kaggle.com/datasets/valkling/tappy-keystroke-data-with-parkinsons-patients/download?datasetVersionNumber=1).
    src/: Source code for the analysis.
    models/: Serialized versions of the trained models. (Currently Hosted at AWS and will be delivered with the link to this notes and that of interactive web/app for your live test/engagement)
    README.md: Overview and instructions.
    .gitignore: List of files and directories ignored by Git.

## Results

The model achieves a 91% cross-validation accuracy and an F1 score of 0.88, showing promise for PD detection. The detailed results are in the analysis notebook near the bottom. That's where our final model sits; we had done a lot with data at the beginning of the notebook and tried several other models before we could settle on the one near the bottom, which was trained with a huge sample of about 600,000 records.

## Visualization

The notebooks include visualizations such as ROC curves and confusion matrices demonstrating the model's diagnostic performance. (The final model we settled for is shown in the last few codes at the bottom of the notebook.)

## Contributing

Your contributions are welcome! For guidelines on how to contribute, please review the CONTRIBUTING.md file.

## Future Directions

The future of this project involves collaboration with medical professionals to refine the model's accuracy further and deploy it in real-world scenarios to aid in early PD detection and ongoing disease management.
Credits

## This project was developed as an academic assignment (B.P) for Noroff University College.

## License

Licensed under the MIT License - see the LICENSE file for more details.
Contact

  ## Fredrick Mburu - frembu63074@stud.noroff.no
  ## Secondary Contact - scurmbu@yahoo.com
