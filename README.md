Whale Song Detection Project
Overview
This project detects whale songs from acoustic data using machine learning models. It includes noise reduction techniques, visualization of spectrograms with detected whale songs, and performance evaluation.

Structure
model_performance.py: Evaluates model performance by calculating precision, recall, and F1-score.
visualization.py: Contains functions to plot spectrograms and overlay detection results.
noise_reduction.py: Implements noise reduction using spectral subtraction.
notebook.ipynb: Main Jupyter notebook where model training, prediction, and analysis are performed.
Usage
Model Performance Analysis: Run evaluate_model_performance(ground_truth, predictions) to evaluate your model.

Improved Visualization: Use plot_spectrogram_with_detections(spectrogram, detections) to visualize whale songs on spectrograms.

Noise Reduction: Apply noise_reduction(audio, sr, noise_clip) to denoise the audio signal before feeding it into the model.

Requirements
librosa
matplotlib
scikit-learn
numpy
Example Workflow
Load your audio data.
Denoise the audio if needed.
Apply the model to detect whale songs.
Visualize the results using spectrograms.
Evaluate the model performance.
Results
After running the notebook, you will get:

Precision, recall, and F1-score of the model.
Spectrograms with detected whale songs highlighted.
Denoised audio for improved model accuracy.
