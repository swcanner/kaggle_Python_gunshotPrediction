Name: Samuel Canner
Username: Danny Devito
Pvt Score: .99531

The names reflect the attempted methods.

cnn1d_simple - simple 1d CNN
cnn1d_noise - I added noise, gaussian normal 1 +/- .03 multiplied by the original feature vector. Went through gunshot data as well to create more instances of the gunshot
cnn2d_simple - reshape the data into a square
librosa_spec - using the noise, created an MFCC from librosa (improved results due to different distribution of frequencies) and did 2D CNN
lstm - Simple LSTM over the original data. Only did simple way since it required a lot of time and I didnt want to wait
spectrogram - scipy spectrogram with 2D CNN. Really didn't work well for whatever reason, but I was able to get librosa to work thankfully.
variational-autoencoder - Single layer autoencoder to a latent dimension to a random forest. Not a lot optimized due to the Librosa Technique providing the solid results

