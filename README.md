# echo-generator
This MATLAB project generates an echo effect for an audio signal. It works as follows:
Converts the desired echo delay from seconds to samples.
Creates a delayed copy of the original audio signal using zero-padding.
Scales the delayed signal by a specified amplitude.
Adds the delayed signal to the original audio to produce the echo effect.
Normalizes the final output if its amplitude exceeds allowed limits.
The function echo_gen implements these steps and produces an audio signal with the echo applied. All implementation details are in the code.
