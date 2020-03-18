
> **DOWNLOAD link: [VoiceData](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v2.0/VOICEDATASetup.exe) The software and the book (the PDF can be downloaded here above) are FREE for non-commercial use!**
>

# VoiceData
VoiceData can be used **for generating data for training Automatic Speech Recognition (ASR) models**. The generated data includes **both with the transcription synchronized audio (the input text is read by a machine trained very human sounding synthethized voice; male or female) and transcription files** for training ASR models in several languages by using any text you desire. **There are a lot of languages and voices (female and male) available.**

VoiceData has a special multiprocessor/core support which makes the toolkit much faster especially when processing several audio files or images at once.

**VoiceData** is Microsoft Windows 64bit compatible (Windows 7, 8 and 10).

> IMPORTANT INFORMATION ABOUT THE REQUIRED SERIAL NUMBER: in case you do not have a serial number then register on the AI-TOOLKIT Helpdesk (see hereunder, please fill in your real name and e-mail) and get automatically the serial number (FREE for non-commercial purposes).
> AI-TOOLKIT HELPDESK: **[AI-TOOLKIT HELPDESK FOR SERIAL NUMBER](https://aitoolkit.freshdesk.com/support/solutions/articles/26000016343)**
>

# Text Normalization
VoiceData text normalization is based on Sparrowhawk/Kestrel, the Google-internal TTS text normalization system reported in Ebden and Sproat (2014). Copyright 2015 and onwards Google, Inc., Apache 2.0 http://www.apache.org/licenses/LICENSE-2.0, Sparrowhawk on GitHub: https://github.com/google/sparrowhawk

The first step in ASR data generation is to normalize the input text. Normalization means that all non text elements (e.g. 1/1/2018 or 10.5kg) must be converted to text. This is a complex task because the normalization must use language dependent grammar definitions in order to be able to detect and normalize such elements automatically. You may also decide to provide the normalized text directly.

**Learn more about the VoiceData text normalization and the grammar definition format from the free book VoiceData Text Normalization.** The book contains an extensive explanation about how to develop language dependent grammars and about many related subjects together with a lot of examples. It is recommended to read the book before using the software.

VoiceData contains grammar definitions for two languages English and Dutch. You can develop your own grammars for any language with the help of the **built in GrammarEditor** (Grammar menu). You can even replace the distributed English and Dutch grammars by replacing the language directories with your own files. Please read the free book VoiceData Text Normalization for more information and examples.

# Export ASR Data (audio & transcriptions)
When you have the normalized text and you have chosen the desired language in the sidebar's Speech tab, then you can use the Export Normalized Audio & Transcriptions command to export the audio and the accompanying text transcriptions automatically per sentence.

# AI Text Synthesizer/Speaker
The synthesizer can read the text present in the Normalized Text editor in several languages. You can select the languages/voices on the Sidebar's Speech tab. You can also install other languages/voices. You can operate the synthesizer from the Speech command center on the Sidebar's Speech tab.

You can also adjust the volume, the rate of speech, you can start, pause, resume and even save the speech in an audio file which you can use to listen to the text later on your computer or on an other device (Smartphone, MP3-player, etc.). You can easily convert the saved WAV file to any other audio format by using the AudioEditor in the AI-TOOLKIT.

