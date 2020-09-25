# assignment_five
Kadenze, Machine learning for musicians and artists

A simple feature extractor using MaxMSP and Wekinator that would recognize certain pitches from a violin and trigger pre-recorded samples in response.

For assignment to work, you will need:

- Max external object "sigmund" which will track pitch input. Please note that there is a minimum amplitude threshold for sending OSC messages to Wekinator to minimize noise.
- audio samples
- an instrument that can output pitches ranging from G below middle C and D three octavos above middle C

1. To start, please "run" wekinator
2. pitches G-middle C will trigger class 1
3. pitches D above middle C up to G will trigger class 2
4. pitches A above middle C up to D will trigger class 3
5. pitches E two octaves above middle C up to B will trigger class 4
6. D three octaves above middle C will trigger the samples to stop

Anna Savery
