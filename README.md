# Onju Voice 🍐🔈 (Modified Version)
This is a modified version of the **Onju Voice** project, originally created by **Justin Alvey**. Onju Voice is a hackable AI home assistant platform based on the **Google Nest Mini (2nd gen)** form factor. My goal is to create my own AI assistant by fine-tuning an open LLM from **Hugging Face**, with specific support for spanish and a customized speaker accent.

## Original project overview
The original project was developed as an experimental conversational AI platform using the **ESP32-S3** for audio processing and a local server to handle transcription, response generation, and Text-to-Speech. This project consists of the following key components:
- **Firmware**: Designed for a custom PCB to replace the Google Nest Mini’s original board, using the **ESP32-S3** for audio processing.
- **Server**: Handles transcription, response generation, and Text-to-Speech for multiple devices on the same network.

## Modifications to the original project
I plan to:
- **Fine-tune an open LLM** from Hugging Face to enhance the conversational abilities of the AI assistant. The fine-tuning process will focus on making the model better suited for my specific use cases and interactions in spanish.
- Integrate **Spanish language support** with the option to fine-tune the LLM for regional language patterns and a specific accent.
- Implement a Text-to-Speech (TTS) system that uses **Spanish voices with a customized accent**, ensuring the AI assistant sounds natural and localized for Spanish speakers.
- Customize the transcription pipeline to handle **Spanish-language speech recognition** with Whisper or other open-source models.

## 🍐 Credits
The original **Onju Voice** project was created by **Justin Alvey**. This version is a modified one with additional features, such as spanish language support and fine-tuning of language models, planned for future implementation.

## Contributions and Feedback
Feel free to contribute by submitting pull requests or opening issues. Feedback and suggestions are always welcome!
