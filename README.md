# Multilingual Speech Recognition and Translation System

Welcome to the Multilingual Speech Recognition and Translation System repository! This project is dedicated to providing a powerful, general-purpose speech recognition model known as Whisper. It's designed to understand and process speech in multiple languages, making it incredibly versatile for various speech-related tasks.

## Features

- **Multilingual Recognition**: Whisper can recognize speech in different languages, making it a valuable tool for global communication.
- **Speech Translation**: Not only does it recognize speech, but it can also translate it, bridging the language gap between different speakers.
- **Language Identification**: The model can identify the language being spoken, which is essential for processing multilingual datasets.


## Getting Started

To begin using Whisper, please follow these steps:

1. **Clone the Repository**: Get a copy of the repository on your local machine.
2. **Explore the Documentation**: Familiarize yourself with the model's capabilities and how to implement them in your projects by clicking here.
3. **Choose a Model**: Select the appropriate Whisper model version for your needs. The current release supports multiple models tailored to different tasks and complexities.

## Contribution

We welcome contributions from the community. If you have suggestions or improvements, please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-sourced under the MIT license. For more details, see the LICENSE file in the repository.

## Contact

If you have any questions or need further assistance, please open an issue in the repository, and I'll get back to you as soon as possible.

Thank you for your interest in our Multilingual Speech Recognition and Translation System!

```markdown

For more details and updates, visit the [Whisper GitHub repository](https://github.com/openai/whisper).

## Supported Models

- **OpenAI Whisper**: [v20231117 release](https://github.com/openai/whisper/releases/tag/v20231117)
- **SYSTRAN Faster Whisper**: [v0.10.0 release](https://github.com/SYSTRAN/faster-whisper/releases/tag/0.10.0)

## Quick Start Guide

### Running on CPU

To deploy the Whisper ASR webservice on a CPU environment, use the following Docker command:

```sh
docker run -d -p 9000:9000 -e ASR_MODEL=base -e ASR_ENGINE=openai_whisper onerahmet/openai-whisper-asr-webservice:latest
```

### Running on GPU

For GPU support, ensure you have the necessary drivers and run the following Docker command:

```sh
docker run -d --gpus all -p 9000:9000 -e ASR_MODEL=base -e ASR_ENGINE=openai_whisper onerahmet/openai-whisper-asr-webservice:latest-gpu
```

## Documentation

Explore the comprehensive documentation to get started and learn more about the Whisper model's capabilities and usage. Click [here](https://github.com/openai/whisper) to access the documentation.

```

## Credits

- This software uses libraries from the [FFmpeg](http://ffmpeg.org) project under the [LGPLv2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html)
