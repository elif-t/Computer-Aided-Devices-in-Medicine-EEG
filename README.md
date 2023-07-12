# Computer-Aided-Devices-in-Medicine-EEG
Analyzing the effect of music listening on EEG functional connectivity of brain.

## The Effect of Music Listening on EEG Functional Connectivity of Brain
Music is a very good stimulus, and it appears to have a cognitive and emotional status, in contrast to others. Music has a powerful effect on the brain; it can regulate mood by enhancing joy and happiness, as well as enhance vigilance. Music can make you feel better, more joyful, and relaxed, but it can also be bothersome and aggravating, leading to stress, hypertension, and impairment of cognitive processes.

EEG data are brain waves that may be separated into several frequency bands. Each of these bands is linked to a certain function in the brain. The brain frequency bands are classified into five groups, according to and the International Federation of Clinical Physiology for Clinical Neurophysiology, as follows:

Alpha activity (α waves): are found in practically every portion of the brain, but predominantly in the occipital lobe, and have a frequency of 8-12 Hz. These waves are strongly related with any feeling of relaxation. Alpha waves are frequently increased during meditation or other stress-relieving activities.

Beta activity (β wave): Beta waves, or brain waves with frequencies ranging from 12 to 30 Hz, indicate an active brain state . These waves arise when performing everyday chores in a normal state of awareness. Low beta waves are observed when we engage in shallow thinking, whereas high beta waves are observed when we are fully focused and competent in tasks that require understanding. As a result, beta activity (wave) is connected to the brain state during cognitive and conscious action .

Theta activity (θ wave): Created during sleep and drowsiness theta waves have a frequency of 4–8 Hz. Theta waves, which are the fastest brain waves, are present in situations involving high degrees of spiritual consciousness and in experiences that elicit higher virtues like love, empathy, and kindness. In this mode, people are at ease, and different ideas flow more easily.

Delta (δ) waves, the slowest brain waves with a frequency range of 0.5 - 4 Hz, are not seen in adult brains while awake. They are more commonly connected with deep sleep and disorders like as hypoxia and schizophrenia. Delta activity (wave) on the other hand is related with the deepest depths of sleep and meditation and has been shown to benefit brain repair and recovery.

Gamma activity (γ wave): are the fastest brain waves, with frequencies greater than 30 Hz. They are linked to better cognitive function, memory, and attention. When a person is deeply concentrating and addressing issues, gamma waves are seen. These waves can also be seen in stroke and epilepsy patients.

### Data Description
The dataset supplied includes electroencephalography (EEG) responses from 20 Indian subjects. The reactions were captured while they were listening to 12 various songs ranging from Indian classical to goth rock. The song number to which each participant listened was labeled on their session. After hearing a single beep, which signaled that the music was about to start, the subjects were told to close their eyes as part of the experiment. The music was then played via speakers, and participants were asked to score their familiarity and enjoyment of the song. They were instructed to open their eyes and rate the situation on a scale of 1 to 5. This was accomplished by giving them a double beep. Using a scale of 1 to 5, the ratings were tallied, with 1 denoting the song as being the most well-known or enjoyable and 5 denoting the opposite. The events chronology in the segmented data should be ignored because it is inherited from the raw data.

[dataset link](https://nemar.org/dataexplorer/detail?dataset_id=ds003774)

### Data pre-processing
The subjects' EEG data were pre-processed using a Python script written with the MNE (MNE-Python) toolkit. Several stages were required in the script to prepare the data for analysis and extract key characteristics. The following is a summary of the pre-processing steps. The required libraries, including MNE, matplotlib, numpy, pandas, and seaborn, were imported to facilitate data analysis and visualization. Participant IDs and session names were defined to identify and organize the EEG data for each participant and session. The raw EEG data for each participant and session were loaded. The data were then stored in a dictionary for easy access and further processing. Specific frequency bands of interest, such as delta, theta, alpha, beta, and gamma, were defined based on their relevance to the study.
After the application of data pre-processing, you can see some sample EEG images below.
Ses-05 sub-01
![Ses-05 sub-01](https://github.com/elif-t/Computer-Aided-Devices-in-Medicine-EEG/blob/main/assets/ses-05_sub-01_eeg.png)
Ses-12 sub-12
![Ses-12 sub-12](https://github.com/elif-t/Computer-Aided-Devices-in-Medicine-EEG/blob/main/assets/ses-12_sub-012_eeg.png)
