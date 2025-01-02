# Text-Speech
This project implements text-to-speech using the Bark small model (suno/bark-small) through Hugging Face Transformers pipeline. Bark is known for its high-quality, natural-sounding speech synthesis.
Features

Natural and expressive speech synthesis
Multiple speaker presets
Multilingual support
Simple pipeline implementation
Memory-efficient using bark-small model

Requirements

transformers
torch
scipy (for audio processing)

Model Information
This project uses suno/bark-small, which is:

A lightweight version of the original Bark model
Optimized for faster inference
Reduced memory footprint
Suitable for production environments

Supported Languages
The model supports multiple languages including:

English
German
French
Spanish
Italian
Portuguese
Polish
Hindi
And more

Voice Presets
Available speaker presets include:

v2/en_speaker_1 through v2/en_speaker_9
v2/multilingual_speaker_1
Additional community-contributed voices
