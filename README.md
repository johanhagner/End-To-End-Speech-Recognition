# End-To-End-Speech-Recognition
End-To-End Speech Recognition using RNNs

6 models was trained and evaluated. The starting point was this project https://github.com/hirofumi0810/tensorflow_end2end_speech_recognition. The corpus used to train the models is the Libri Speech corpus [http://www.openslr.org/12]

Models with GRU, LSTM and LSTM with peepholes was trained on:
- Train-clean-100, total
- Train-clean-100 + Train-clean360 + Train-other-500, 960 hours total

The training logs, transcribed testing sets, and graphs during training is provided in the results folder.

In the samples folder there are 16 audio samples from the test-clean and test-other sub sets and the corresponding transcription text files.

The modified code used for running is yet to be uploaded
