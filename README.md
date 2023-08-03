# Persian Classical Music Instrument Recognition

### Dataset : PCMIR by Mousavi, S. M. H., et.al. > [paper_link](https://www.researchgate.net/profile/Surya-Prasath/publication/336810669_Persian_Classical_Music_Instrument_Recognition_PCMIR_Using_a_Novel_Persian_Music_Database/links/5e3b6aaca6fdccd9658a824d/Persian-Classical-Music-Instrument-Recognition-PCMIR-Using-a-Novel-Persian-Music-Database.pdf)

### The step by step procedure for instrument recognition is explained in jupyter file. In summary:
* Load the dataset and create the melspectograms using librosa library
* Implement a generator object to load resulting mels
* Define the model architecture and other training components
* Create a temporal version of previous model to get instrument distribiution over time


### The model achieves __precision and recall of .902 and .896 on test set__, respectively.


### Future work:
### Implementation of a backend service to show instrument distribution in a chart alongside playing the actual audio stream.



