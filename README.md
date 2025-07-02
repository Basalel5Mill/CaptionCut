<p align="center">
  <img src="https://github.com/user-attachments/assets/330639c0-248c-489f-8422-09fbef5cfda8" alt="Captioncut" width="100"/> 
</p>

<p align="center">
  <strong>Caption Cut FCPX Extension</strong>
</p>

## Description

Caption Cut is a Final Cut Pro  Extension designed to automatically generate captions from your audio files. Simply provide an MP3, choose your language and AI model, select a Motion Template, and Caption Cut uses Whisper AI to transcribe the audio and create styled title captions directly in your FCPX project. Customize the look with font, size, and color options for seamless integration.

[Download Caption Cut](https://basalel.gumroad.com/l/hieqr)

[Download Caption Cut Pro](https://www.captioncut.com/)




## Features

![Configure](https://github.com/user-attachments/assets/705be0e9-33d9-415d-affd-3c1b2f059045)


* **Automatic Transcription:** Uses the Whisper AI engine to convert speech from MP3 files into text captions.
* **Multi-Language Support:** Select from a wide range of languages for transcription.
* **Selectable AI Models:** Choose different Whisper model sizes (Tiny, Base, Small, Medium, Large) for varying speed and accuracy. Models may require download on first use.
* **Motion Template Integration:** Generates captions as styled FCPX Motion Titles using installed templates.
* **Customizable Appearance:** Adjust Font, Size, Color, and Text Width for captions within the extension.
* **Text Formatting:** Option to automatically split transcribed text into lines based on word count (1, 2, or 3 words per line).
* **Direct FCPX Import:** Sends the generated caption titles (as FCPXML) directly back to Final Cut Pro for easy import.
* 
![Process](https://github.com/user-attachments/assets/5c2777ab-8ed3-4a48-b901-d243dc6abefe)



## Requirements

* macOS
* Final Cut Pro
* Caption Cut Motion Templates (The main Caption Cut app should install these automatically on first run)
* Whisper AI Models (These can be downloaded as needed from within the extension UI)
* Internet connection (for downloading AI models).


1.  Open your project in Final Cut Pro.
2.  Click the Extensions icon in the FCPX toolbar (looks like a puzzle piece) and select "Caption Cut".
3.  Configure your desired settings in the Caption Cut extension window:
    * **Language:** The language spoken in your audio file.
    * **Model:** The Whisper AI model size (e.g., Base, Small, Medium). Larger models are generally more accurate but slower.
    * **Word Per Line:** How many words to display per caption line (e.g., "One line", "Two lines").
    * **Font, Color, Size, Text Width:** Customize the appearance of the captions.
    * **FPS, Resolution:** Match these to your FCPX project settings.
    * **Title Style:** Select the installed Motion Template to use for the caption appearance.
4.  Drag & drop your MP3 audio file onto the drop zone, or click to browse and select the file.
5.  Click the "Create" button.
    * *Note:* If this is the first time using the selected AI Model, you will be prompted to download it. This requires an internet connection.
6.  The extension will process the audio (convert, transcribe, format). Progress and status updates will be shown.
7.  Once processing is complete (Status: "Done"), click the "Add to Timeline" button.
8.  Final Cut Pro will prompt you to import the generated FCPXML file containing the caption titles. Choose your desired library/event.
9.  The captions will appear as titles on the timeline in your FCPX project.

