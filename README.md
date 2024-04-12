# Simple sound analyzer
---
This project is based on matlab app designer. It's main function is to record voice and show the frequency-domain signal by FFT. 
The project is very simple, just as a try for pushing my repo.

Following is a tidy introduction of the proj:
1. Modules
   - UIAxes
     - The upper image shows time-domain signals input in last step. 
     - The lower one shows the frequency-domain signals, which is also named "spectrum".
   - Buttons
     - Record: recording the sound.
     - Play: playing the recorded audio data.
     - Frequency-analysis: displaying the spectrum of the signal .
     - Add-noise: adding Gaussian noise to the signal to generate noisy speech signal.
     - moving average filter

2. Operations
   - press the "Record" button and record your sounds.
   - press the "Play" button and play the audio.
   - press the "Frequency-analysis" button
   - press the "Add-noise" button. Both  time-domain and frequency-domain image of the noise signal will be shown.
   - press the "moving average filter" button. Both  time-domain and frequency-domain image of the disnoised signal will be shown.
   - you can also choose to slide blocks to change the window size. The digits below just mean the relative value instead of the exact parameter. 

