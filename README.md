# Background
Humans and animals integrate visual inputs from both eyes in the primary visual cortex (V1) to construct a three-dimensional perception of the world. Our primary goal is to understand the computations underlying such binocular integration. To this end, this code implements the Spike-Triggered Average (STA) method to calculate and visualize binocular receptive fields from real neuronal electrophysiological data.

# Model and Methods
The classical model of binocular integration for a single cortical neuron is the Energy Disparity Model. It follows a Linear–Nonlinear (LN) architecture: inputs from the two eyes are first summed linearly and then passed through a nonlinear output function.
This code applies STA to compute receptive fields from recordings of mouse V1 neurons responding to grating stimuli.
<img width="397" height="489" alt="image" src="https://github.com/user-attachments/assets/b9826b17-af70-4d8f-ad53-d6000d22986e" />

# Application
This code can be used to perform STA analysis to calculate receptive fields for both binocular and monocular neurons across different experimental subjects. This code is specifically designed for electrophyscial recording data on animals. 





