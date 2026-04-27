# Child Screen Time Addiction Predictor

## Project Idea
This micro project uses supervised machine learning to predict a child's addiction level from screen-time related features. The predicted addiction level is then combined with age to generate a short future-impact description using an external open-source AI API.

## Algorithm Used
- Supervised Learning
- k-Nearest Neighbor (kNN) classifier

## What the Program Does
1. Reads the dataset from `child_screentime_dataset.csv`.
2. Trains a kNN classifier to predict `AddictionLevel` from the other columns.
3. Evaluates the model using train-test split, cross-validation, accuracy, and confusion matrix.
4. Uses the predicted addiction level and age to request a future-impact paragraph from Hugging Face Inference API.

## Syllabus Mapping
- Unit 1: Introduction to Machine Learning
- Unit 2: Pandas, Matplotlib, Scikit-learn
- Unit 3: Model preparation and evaluation
- Unit 4: Supervised Machine Learning and kNN
- Unit 5: Generative AI through external AI-based impact text

## Files
- `main.ipynb` - main Python program
- `child_screentime_dataset.csv` - dataset

## How to Run
1. Install the required packages from `requirements.txt`.
2. Run the notebook
OR
Google Colab link: [CLICK HERE](https://colab.research.google.com/drive/1Hhd2WLCOV2usfXdNtUxN-Z0bCcs75jYh)

## Notes
- The model predicts `AddictionLevel` from 1 to 5.