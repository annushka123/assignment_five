https://github.com/annushka123/assignment_five.git

This is my assignment no 5, creating your own feature extractor - Kadenze Machine learning for musicians and artists

My goal was to create a  simple feature extractor using MaxMSP and Wekinator that would recognize certain pitches from a violin and trigger pre-recorded samples in response.

For assignment to work, you will need:

- MaxMSP and Wekinator
- Max external object "sigmund~" which will track pitch input. Please note that there is a minimum amplitude threshold for sending OSC messages to Wekinator to minimize noise.
- audio samples
- an instrument that can output pitches ranging from G below middle C and D three octavos above middle C

1. To start, please open Max input and output patches and "run" wekinator (make sure sound is on in Max)
2. pitches G-middle C will trigger class 1
3. pitches D above middle C up to G will trigger class 2
4. pitches A above middle C up to D will trigger class 3
5. pitches E two octaves above middle C up to B will trigger class 4
6. D three octaves above middle C will trigger the samples to stop

Although this is a simple patch that does very little, it is a stepping stone to fuse projects involving violin and machine learning.

Anna Savery


