# Overall description:
The API will contain all the algorithms and I/O that is used in the pipeline for detecting pulsars, This pipeline is:
1. Read input from a filterbank file 
2. Dedisperse and/or downsample the input time series
3. Detect single pulses with high signal-to-noise ratio (SNR)
4. Use FFT to detect periodic signals with high SNR
5. Fold candidates with the best SNR at the right period
6. Save the folded candidates

[Back to table of contents](../readme.md)