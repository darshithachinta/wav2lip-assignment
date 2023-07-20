# wav2lip-assignment
Problem Statement - Synchronizing an audio file with a video file.

As a part of the process, a pre-trained model is taken to test against the given sample input files.
The prerequisites for the model to work fine is to have the video resolution less than or equal to 720p, or the model will resize it to 720p.
The duration of the video file has to be less than or equal to 60 seconds.
The duration of the audio file has to be 20% less than that of the duration of the video file.
The video file must contain a continuous face image or else the model will crash. No blank or any other images are supported.
Keeping all of this in mind, A cropped input file of 0.7 seconds has been taken from the given sample input and tested using the model.

Firstly all the dependencies and required installations are being downloaded.
The input files are loaded into the Google collaboratory and uploaded their custom path into the model.
After all, these are done, the sample inputs are tested against the model, and the output is generated.

The output file of the model is added to the repository.
