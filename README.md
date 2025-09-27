## Facial-Expression-Analysis
This project implements facial expression analysis with CNNs, including expression classification and valence-arousal prediction.

## Project Structure
Facial-Expression-Analysis/
├── Dataset/
│ └── Dataset/
│ └── images/ # Image dataset for training/testing
├── checkpoints/ # Model checkpoints and logs
├── a1.ipynb # Main Jupyter Notebook for analysis
├── .gitignore # Git ignore file
└── README.md # Project documentation

## Datast Information
The dataset contains:
Images: 224x224 RGB face images (3,999 total)
Annotations:
Expression labels (0-7): Neutral, Happy, Sad, Surprise, Fear, Disgust, Anger, Contempt
Valence values: [-1, +1] (negative to positive)
Arousal values: [-1, +1] (calm to excited)
68 facial landmarks per image

## Dataset Splits
Training: 80%
Validation: 20%
