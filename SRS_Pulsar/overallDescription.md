# Overall description:
The API will contain all the algorithms and I/O that is used in the pipeline for detecting pulsars, This pipeline is:
1. read input from a filterbank file 
2. dedisperse and/or downsample the input time series
3. detect single pulses with high signal-to-noise ratio (SNR)
4. use FFT to detect periodic signals with high SNR
5. fold candidates with the best SNR at the right period
6. save the folded candidates