# MDC-CNN
A multi domain connectome CNN for seizure prediction. PLV and TE are used for feature extraction, PCC is optional. More feature extraction processes may be added later.
This repository is dedicated to Seizure prediction using Multi Domain Connectome CNN (MDC-CNN), data from the TUH-EEG corpus is used for EEG data

Here we are using a MDC-CNN with two channels as inputs and uses them for predicting seizures. Thus intead of a single input, 2 inputs are present, this can be increased
to many more chennels. For the further modification to the CNN architecture, follow the flow and do the modifications according. The CNN predicts 1 if a Seizure is
present and 0 if no seizures are found.

Multi_CNN is a basic code for checking if MDC-CNN is working properly.
MUlti_CNN_FS uses sampling frequency which is calculated from the .tse files(annotation files) which are provided with the TUH-EEG database.
 
