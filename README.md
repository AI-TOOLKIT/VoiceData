
> **DOWNLOAD link: [VoiceData](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v2.0/VOICEDATASetup.exe) The software and the book are FREE for non-commercial use!**
>

# VoiceData
VoiceData can be used **for generating data for training Automatic Speech Recognition (ASR) models**. The generated data includes **both with the transcription synchronized audio (the input text is read by a machine trained very human sounding synthethized voice; male or female) and transcription files** for training ASR models in several languages by using any text you desire. Text can also be extracted from images e.g. imported from a scanner in several languages. You can scan a book or business papers with text and images. VoiceData has built-in scanner and text recognition support (trained machine learning models for text recognition in several languages). **There are a lot of languages and voices (female and male) available.**

VoiceData also includes a **built-in audio editor** which can not only be used to edit, visualize and convert your audio files but also to **transform the voice recordings**. The audio editor can change the **sample rate, the number of channels, can suppress noise, can cancel echo, change the tempo, change the rate, change the pitch frequency** and it can also remove audio sections without human voice.

VoiceData has features which makes it possible to completely **transfer the audio recording from the base voice to any other type of voice**. For example you could change the pitch and the rate of the audio with the built-in audio editor and transfer an adult voice to a child voice.

VoiceData has a special multiprocessor/core support which makes the toolkit much faster especially when processing several audio files or images at once.

**VoiceData** is Microsoft Windows 64bit compatible (Windows 7, 8 and 10).

> IMPORTANT INFORMATION ABOUT THE REQUIRED SERIAL NUMBER: in case you do not have a serial number then register on the AI-TOOLKIT Helpdesk (see hereunder, please fill in your real name and e-mail) and get automatically the serial number (FREE for non-commercial purposes).
> AI-TOOLKIT HELPDESK: **[AI-TOOLKIT HELPDESK FOR SERIAL NUMBER](https://aitoolkit.freshdesk.com/support/solutions/articles/26000016343)**
>

> **DOWNLOAD link: [VoiceData & Book](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v1.1/VOICEDATASetup.exe) The software and the book are FREE for non-commercial use!**
>

# Text Normalization
VoiceData text normalization is based on Sparrowhawk/Kestrel, the Google-internal TTS text normalization system reported in Ebden and Sproat (2014). Copyright 2015 and onwards Google, Inc., Apache 2.0 http://www.apache.org/licenses/LICENSE-2.0, Sparrowhawk on GitHub: https://github.com/google/sparrowhawk

The first step in ASR data generation is to normalize the input text. Normalization means that all non text elements (e.g. 1/1/2018 or 10.5kg) must be converted to text. This is a complex task because the normalization must use language dependent grammar definitions in order to be able to detect and normalize such elements automatically. You may also decide to provide the normalized text directly.

**Learn more about the VoiceData text normalization and the grammar definition format from the free book VoiceData Text Normalization.** The book contains an extensive explanation about how to develop language dependent grammars and about many related subjects together with a lot of examples. It is recommended to read the book before using the software.

VoiceData contains grammar definitions for two languages English and Dutch. You can develop your own grammars for any language with the help of the **built in GrammarEditor** (Grammar menu). You can even replace the distributed English and Dutch grammars by replacing the language directories with your own files. Please read the free book VoiceData Text Normalization for more information and examples.

# Export ASR Data (audio & transcriptions)
When you have the normalized text and you have chosen the desired language in the sidebar's Speech tab, then you can use the Export Normalized Audio & Transcriptions command to export the audio and the accompanying text transcriptions automatically per sentence.

# AudioEditor
The AudioEditor can be used to **view** (also **zoom in/out**) the **waveform** of the audio, the **spectrogram** and also to view the properties of the audio (sample rate, encoding, etc.). Many audio file formats are supported as for example **wav, mp3, etc.** Please note that the following wav file formats are supported: 16, 24 or 32 bit PCM or IEEE float audio data.

The AudioEditor is optimized for short audio files but can also handle longer audio of several hours.

You can zoom in both diagrams with the left mouse button several levels deep.

In case you want to **save only a specific part of the audio file** then select that part and click the 'Save Audio Selection' button (hover above the buttons to see a tooltip).

You can save the audio in mp3 or wav format.

You can also record an audio. Select the recording properties in the right control panel.

Longer audio files, or when zoomed in, are shown on several pages. You can walk through the pages with the left, right and start, end buttons at the top right corner of the waveform diagram. Both diagrams are handled in sync while stepping through the pages or when zooming.

## AudioEditor Transform Audio
With this module you can transform the properties of a wav audio file. You can select any number of transformation options at the same time. The properties for each transformation are in the right control panel. 

Please note that the following wav file formats are supported: 16, 24 or 32 bit PCM or IEEE float audio data. The sample rate must be divisible by 100 for several of the transformation options. In case your wav file does not comply with this requirement then you must first convert it with the Change Sample Rate transformation option. See the right control panel for the available standard sample rates.

You can apply the transformations to several selected files (Transform Selected Files) or to a whole folder (Transform Files in Folder). The transformations will be done in batch mode and by making use of several processors if available.

### Change the Sample Rate, the Number of Channels, the Tempo, the Rate
All of these transformation options are applicable separately or all together!

### Suppress Noise and Echo Cancellation
Suppress noise will remove noise from the audio depending on the selected suppression level (right control panel). 0 means no noise removal, 3 highest level of noise removal. Echo removal works similarly but with three strengths (low, moderate and high).

### Change Pitch
This transformation can be used to adjust the pitch (fundamental frequency) of the audio to a specific key frequency defined in the right control panel. The voiced speech of a typical adult male will have a fundamental frequency from 85 to 180 Hz, and that of a typical adult female from 165 to 255 Hz. Infants show a range of 250 to 650 Hz. By using these values you can change e.g. an adult voice to an infant one or a male voice to a female like voice.

### Remove Audio without Human Voice
This transformation will remove the parts of the audio in which human speech can not be detected.

### Audio File Conversion
You can also choose the output file type as wav or mp3 while applying the above transformations.

The 'Convert To WAV Without Encoding (PCM)' command can be used to batch convert several audio files from one audio format to WAV PCM format without encoding. Several input audio formats are supported also depending on your system's configuration (installed encodings). The WAV PCM format without encoding is the audio format which is used by most of the AI-TOOLKIT software (VoiceData, VoiceBridge, etc.).

> **DOWNLOAD link: [VoiceData & Book](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v1.1/VOICEDATASetup.exe) The software and the book are FREE for non-commercial use!**
>

# AI Text Recognition
You can load any image with text on it in a specific language and extract the text. The AI is trained to recognize text in images in several languages. You can select the language on the Settings | Text tab of the sidebar. The installation only provides English because of the size of the data files but you can download and install many other languages easily and for free.

# Image Enhancement
You can load any image or several images and you can enhance them one by one or all at the same time. In case you have several processors or processor cores in your computer the AI can take advantage of this extra computing power. Set the number of processors/cores in the Settings | General tab.

There are two images on the screen, 'Original Image' which is the original image(s) you open, and 'Cleaned Image' which is the image with all image enhancements applied. Both of the images may contain one or more images (only one image is visible). You can select the visible image with the 'First page', 'Former Page', 'Next Page', 'Last Page' commands on the toolbar or in the menu. You can also save both collection of images with the Save command in the File menu. The images can be zoomed in with the mouse scroll wheel or with the buttons in the top-right corner of the image boxes, or can be panned with holding down the left mouse button and dragging the mouse.

## Image Enhancement Options:
- **Reset Image** : this command will reset the Cleaned Image to its original state.
- **Apply To All Pages** option is on the Settings | Image1 tab. When checked all currently loaded images will be enhanced at the same time (batch processing).
- **AUTOCLEAN** : this command contains several pre-defined image enhancements. You can select the preferred preset in the Settings | Image3 tab.
- **Despeckle** : removes noise from the image. The width and the height of the filter in the Settings | Image2 determines the level of detail the enhancement will remove.
- **Brighten** : makes the image brighter. The strength of the effect can be selected in Settings | Image1.
- **Darken** : makes the image darker. The strength of the effect can be selected in Settings | Image1.
- **Flip vertically or horizontally**.
- **Contrast adjustment**. The strength of the effect can be selected in Settings | Image1.
- **Sharpen** or the application of the Unsharp mask to make details more visible. The strength of the effect can be selected in Settings | Image1.
- **Deskew** : this will make the text straight.
- **Gamma correction** : this can make the image look lighter or darker. The strength (gamma) of the effect can be selected in Settings | Image2.
- **Auto-crop** : this will remove the unnecessary space around the text. The color tolerance (what is considered as not necessary) and the margin in pixels which will not be removed can be selected in Settings | Image2.
- **Remove H/V Lines** : this will remove horizontal and vertical lines from the image and will also transform the image to grayscale. The solidify factor in pixels of the effect can be selected in Settings | Image2. The solidify factor (the width of the effect around the lines) should not be chosen to high because then you will loose too much from the underlying text.
- **Remove Lines Alfa**: this will remove angled lines from the image and will also transform the image to grayscale. The solidify factor in pixels (the width in pixels the lines will be widened while erasing the lines) and the alpha rotation degree can be chosen in Settings | Image2. Please note that the image will be enlarged in order to accommodate the extra space necessary because of the rotation!
- **Rotate** : this will rotate the image with the angle selected in the Settings | Image1. Please note that the image will be enlarged in order to accommodate the extra space necessary because of the rotation!

# AI Text Synthesizer/Speaker
The synthesizer can read the text present in the Normalized Text editor in several languages. You can ask the AI to recognize and then read the text on an image or you can also load, copy/paste or type text in the editor and listen through the computer speakers. You can select the languages/voices on the Sidebar's Speech tab. You can also install other languages/voices. You can operate the synthesizer from the Speech command center on the Sidebar's Speech tab.

You can also adjust the volume, the rate of speech, you can start, pause, resume and even save the speech in an audio file which you can use to listen to the text later on your computer or on an other device (Smartphone, MP3-player, etc.). You can easily convert the saved WAV file to any other audio format by using the built-in AudioEditor.

# Using the Scanner
The scanner toolkit automatically recognizes your scanner when it is switched on before starting the software. If you switch on your scanner after you start the software then just press the Scan button to start the scanning and VoiceData will automatically recognize the scanner. All options can be set on the Sidebar's Scanner command center (the source, paper size, resolution, type of document). Select a higher resolution if you still want to enhance the image because that will result in a better final image. You can scan as many pages as you want (only limited by computer resources) and you can also use the automatic feeder on your scanner (selectable as source).

# Using the Screen Capture
The Screen capture feature on the Capture tab of the Sidebar can capture your computer's screen. Set the Timeout to greater than 0 seconds in order to delay the screen capture. You will have then time to navigate to another screen.

# Preparing a Collage of Images
You can easily create a collage (matrix) of images from several open images. This kind of collage can be e.g. used to train the VisionAI AI engine.

> **DOWNLOAD link: [VoiceData & Book](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v1.1/VOICEDATASetup.exe) The software and the book are FREE for non-commercial use!**
>

# VoiceData UI
The VoiceData UI is designed to make your work easier and intuitive. There is also a built-in Help in the right sidebar.

![VoiceData UI](https://4.bp.blogspot.com/-8To31j0p_xc/WtiBFh0HfEI/AAAAAAAAA24/tqwgSIZ2TGMZ9-T2_KlkXEHCsH1UHa5tACK4BGAYYCw/s1600/VoiceData1.png)

The Audio Editor:

![Audio Editor](https://1.bp.blogspot.com/-URytHxw9sPc/WtiBMJRiJ2I/AAAAAAAAA3A/zyanDWepl5AQ81ElRaQceVVCYg6ovjuXACK4BGAYYCw/s1600/AudioEditor1.png)

The Grammar Editor:

![Grammar Editor](https://3.bp.blogspot.com/-W_enR27rZrw/WtiBPusW5uI/AAAAAAAAA3I/OfC8K_Wfn1Q4Sc3oCoZfLBl-B8q7dUhiQCK4BGAYYCw/s1600/GrammarEditor.png)

> **DOWNLOAD link: [VoiceData & Book](https://github.com/AI-TOOLKIT/VoiceData/releases/download/v1.1/VOICEDATASetup.exe) The software and the book are FREE for non-commercial use!**
>
