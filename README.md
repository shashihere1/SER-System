# SER-System
# Speech Emotion Recognition (SER)

This project focuses on identifying emotions from speech audio files using machine learning techniques. It involves feature extraction, visualization, and classification to build a robust Speech Emotion Recognition (SER) system.
![spectogram](https://github.com/user-attachments/assets/841adbc0-fe8a-4036-9be9-a47d3c595c03)

## Features
- **Emotion Classification:** Recognizes emotions such as Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.
- **Feature Extraction:** Utilizes Mel-Frequency Cepstral Coefficients (MFCC) to represent audio data.
- **Visualization:** Generates waveplots and spectrograms for understanding audio patterns.
- **Model Performance:** Achieved an accuracy of XX% using a Random Forest classifier.

## Dataset
The project uses the **SAVEE** dataset. Each audio file is labeled with an emotion, which is mapped based on the filename convention.

### Emotion Mapping
| Code | Emotion    |
|------|------------|
| a    | Angry      |
| d    | Disgust    |
| f    | Fear       |
| h    | Happy      |
| n    | Neutral    |
| sa   | Sad        |
| su   | Surprise   |

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Place the SAVEE dataset in the specified directory structure:
   ```
   /ALL/
   ├── DC_a01.wav
   ├── ...
   ```
2. Run the feature extraction and classification script:
   ```bash
   python ser_classification.py
   ```
3. Visualize audio features:
   ```bash
   python audio_visualization.py
   ```

## Project Structure
- `ser_classification.py`: Main script for feature extraction, model training, and testing.
- `audio_visualization.py`: Script for generating waveplots and spectrograms.
- `requirements.txt`: Python dependencies.

## Key Steps
1. **Feature Extraction:**
   - Extracted MFCC features from each audio file.
   - Computed mean values for dimensionality reduction.

2. **Visualization:**
   - Plotted waveforms and spectrograms to analyze audio patterns.

3. **Model Training:**
   - Used Random Forest classifier for emotion prediction.
   - Evaluated model performance with accuracy and classification reports.

## Results
- Achieved an accuracy of XX% on the test set.
- Detailed classification report available in the logs.

## Challenges
- Addressed imbalanced dataset by careful preprocessing.
- Tackled noisy audio through robust feature extraction.

## Future Work
- Improve generalization with additional datasets.
- Explore deep learning models for enhanced performance.
- Implement real-time emotion recognition.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or feedback, contact [Shashi Prakash](mail2shashi123456@gmail.com).

---


