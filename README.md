# Whisper Speech Recognition on ReRAM Crossbar
This Project is a collaboration between Varun Manjunath and Jayanth Balasubramanian under the guidance of Prof.Bhaswar Chakrabarthi, IIT Madras

This project implements the Whisper Tiny speech recognition model on a ReRAM (Resistive Random Access Memory) crossbar array using the `aihwkit` library for analog hardware acceleration. The model is trained and evaluated on the LibriSpeech dataset.

## Overview

Whisper is a transformer-based sequence-to-sequence model developed by OpenAI for robust speech recognition. This project focuses on implementing the Tiny variant of the model, which has 39 million parameters, on ReRAM crossbar arrays for efficient inference.

## Key Features

- Implementation of Whisper Tiny model on ReRAM crossbar using `aihwkit`
- Training and evaluation on the LibriSpeech dataset
- Support for analog inference with customizable ReRAM configurations
- Evaluation of model robustness under various noise conditions

## Usage

To run the code, execute the `Whisper_on_Librispeech.py` script with the desired command-line arguments:

```bash
python Whisper_on_Librispeech.py [--digital] [--ideal] [--wandb] [--noise NOISE] [--run_name RUN_NAME] [--train_hwa] [--load] [--checkpoint CHECKPOINT] [--learning_rate LEARNING_RATE]
