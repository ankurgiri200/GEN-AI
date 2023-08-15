# GEN-AI

TASK 1: DATA PREPROCESSING AND COLLECTION

1. Data Collection:
Let's assume you're collecting 50 Taylor Swift songs and 50 songs from various other artists for your initial dataset.

2. Audio Preprocessing:

Convert audio files to a consistent format (e.g., WAV).
Normalize audio levels to a common scale.
Segment songs into smaller parts (e.g., 30-second segments).
Extract features like spectrograms or MFCCs from the audio segments.
3. Text Data Preprocessing:

Use an online lyrics API to extract lyrics for each song.
Tokenize and clean the lyrics, removing special characters and whitespace.
Create a mapping between each audio segment and its corresponding lyrics.
4. Aligning Audio and Lyrics (Optional):

You might use techniques like dynamic time warping to align audio segments and their corresponding lyrics if you plan to synchronize the music and lyrics.
5. Dataset Creation:

Pair each audio segment from Taylor Swift with its corresponding lyrics.
Pair each audio segment from other artists with its corresponding lyrics.
This results in 100 pairs of audio segments and lyrics.
6. Data Splitting:

Split your dataset into training (80%) and validation (20%) subsets.
7. Ethical Considerations:

Ensure you have the necessary rights to use the audio and lyrics from the collected songs.
8. Data Augmentation (Optional):

Apply data augmentation techniques to the audio segments, such as pitch shifting or time stretching, to enhance the diversity of your dataset.
9. Training Iteration:

Depending on the results, you might decide to collect more data, adjust preprocessing steps, or fine-tune the model architecture.