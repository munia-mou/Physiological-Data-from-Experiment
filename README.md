# Physiological-Data-from-Experiment
This dataset contains processed physiological signals and labeled emotional states collected from seven individual participants during an experimental protocol. Each CSV file represents data from one participant and is stored in the labeled_physiological_data folder which can be found here:
https://uscedu-my.sharepoint.com/:f:/g/personal/ferdoush_usc_edu/Evk3dMJVBWlBl7RT56fmBjkBrvdt7LUrzeAjqpD8UO-sqQ?e=wZp69Y


📁 Files Included

Participant_1.csv

Participant_2.csv

Participant_3.csv

Participant_4.csv

Participant_5.csv

Participant_6.csv

Participant_7.csv


🔬 Data Collection Summary:
Data was recorded using Shimmer wearable sensors and Consensys software.

Participants were exposed to different emotional stimuli or performed various tasks.

Signals include Galvanic Skin Response (GSR) and Photoplethysmogram (PPG).

Each data point is labeled with the corresponding emotional or cognitive state.

🧪 Features Included in Each File
Column Name	Description
Shimmer_FCF4_TimestampSync_Unix_CAL:	Original timestamp from the sensor in Unix time format

time_in_minutes:	Time since start of recording, in minutes

Shimmer_FCF4_GSR_Skin_Conductance_CAL:	Raw GSR signal (skin conductance)

Shimmer_FCF4_PPG_A13_CAL:	Raw PPG signal (infrared component)

Normalized_GSR:	GSR signal normalized (e.g., min-max scaled)

Normalized_PPG:	PPG signal normalized

rmssd:	Root mean square of successive differences (HRV feature)

Event_Label: 	Original label describing participant's state (e.g., "Relaxed", "Stress")

The unique labels in the Event_Label columns are:

Relaxation, CPT Test, Stroop Test, Math Test, Video 1 (Sad video), Video 2( Funny video).
For brinary stress classification, Relaxation, Video1 and Video 2 can be non stress states while the rest are stress state.


