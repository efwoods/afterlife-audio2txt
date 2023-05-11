# afterlife-audio2txt

## Summary
This repository enables individuals to leverage their _passively_ recorded audio to create text to train a neural network. 

The audio will be separated by speaker automatically. It will take 31 hours of actively speaking to collect enough data to sufficiently train a robust neural network. This will inevitably happen, however, this repository allows the ease of collecting the data for non-celibrities and others whose data is scarce.

## Purpose
Training a neural network requires a sufficient amount of text. To train a quality neural network, 200,000 words must be used. Social media has restrictive policies on how people can scrape or use their data from these social networking sites to train AI, and unless you are a celebrity, you will most likely not have enough data available to train a neural network to generate text that is akin to your likeness. 

## Process
1. An initial recording of an individual's voice is required to establish a baseline. This baseline can be used to identify if the current speaker is you or not in a new audio file. 
2. This next audio file is separated by speaker. 
3. The audio is then compared against the baseline to identify if the recognized speaker is you. 
4. The audio of the recognized speaker is then translated into text which can be used to train a neural network. 
