# Mental-Stress-Detection-using-EEGNet
his project classifies mental stress levels from EEG recordings using an EEGNet Convolutional Neural Network architecture. The model is trained on a 5-class dataset and evaluates subjects under various cognitive and emotional states.

## Dataset
The model was trained on the "An EEG Recordings Dataset for Mental Stress Detection", predicting across 5 categories:
1. Complex Mathematical Problem solving (CMPS)
2. Horror Video Stimulation
3. Participants Listening to Relaxing Music
4. Stroop Colour Word Test (SCWT)
5. Trier Mental Challenge Test (TMCT)

## Results
The custom EEGNet model was evaluated using 5-Fold Stratified Cross-Validation and achieved a top-fold accuracy of **95%**, showcasing high precision and recall across all cognitive tasks.

## Setup
1. Clone this repository: `git clone https://github.com/your-username/EEG-Stress-Detection.git`
2. Install the required dependencies: `pip install -r requirements.txt`
