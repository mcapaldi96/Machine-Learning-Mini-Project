# Machine-Learning-Mini-Project

The cohort taking the Principles of machine learning module (ECS7020P) submitted recordings humming and whistling
multiple times to famous songs, these included the Harry Potter, Star Wars and The Pink Panther's theme songs, in 
addition to The Lion Kings famous Hakuna Matata and Abba's hit record Mamma Mia.
The notebook within this repository is well descripted but as an overview of the task the following steps executed.

- Each songs data was read into the notebook.
- Function 'getXy' extracted features and labels from the audio files.
- All features and labels were concatenated into a large dataframe containing all songs.
- The values within the dataframe were normalised using sklearns StandardScaler().
- Models were ran using raw and scaled data to assess the difference in performance.
- Feature selection was used to optimize performance of the models.
- A simple neural net also train and predict the songs audio files.
