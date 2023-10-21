# SongGenreClassifier

Goals: Classifies niche and closely related subgenres of electronic music. Converts audio to Mel spectograms and performs image classification to determine subgenre
##### (Contact me to see the code, it isn't public right now: howe.gaged@gmail.com)

Progress:
* Connect Google Colab to my data
* Function to convert all MP3 files to an n-seconds-long WAV segment chosen by average loudness (LUFS) (reduced processing time and storage requirements of previous implementation by 3000%)
* Function to make a mel spectrogram from each segment with FFT magic

To Do: 
* Organize data according to genre with Pandas dataframes
* Implement and train semi-supervised clustering model on existing data
* Evaluate accuracy
* Fine-tune and optimize functions and model (spectrograms are very noisy)

Tools:
* pandas
* torchaudio - transforms
* torchvision
* pydub - AudioSegment
* os
* matplotlib


<img width="528" alt="Screenshot 2023-10-21 at 12 29 11 PM" src="https://github.com/GageHoweTamu/SongGenreClassifier/assets/116420022/7be5abb2-7040-4ed1-94a3-8d7364ffbe85">

<img width="604" alt="Screenshot 2023-10-21 at 12 26 54 PM" src="https://github.com/GageHoweTamu/SongGenreClassifier/assets/116420022/af8333c9-0b7b-41b2-8eb8-7a5f040a1eef">
