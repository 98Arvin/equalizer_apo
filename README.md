# Peace EQ Presets (Equalizer APO)
================

**Repository Overview**
------------------------

This repository is a collection of my personal Equalizer APO presets for various headsets I use. The goal is to keep track of my preferred EQ settings for each headset, allowing me to easily switch between them and maintain a consistent listening experience.

**What is Equalizer APO?**
-------------------------

Equalizer APO is a free, open-source equalizer software for Windows that allows users to adjust the frequency response of their audio output. It's a powerful tool for fine-tuning the sound of your headphones or speakers to your liking.

**Preset Format**
----------------

Each preset file is in the Equalizer APO format, which is a simple text file containing the frequency response data. You can import these files directly into Equalizer APO on your machine.

**Adding Presets to Your Config Folder**
---------------------------------------

To add these presets to your own config folder, follow these steps:

1. **Locate Your Equalizer APO Config Folder**:
    - The config folder for Equalizer APO is usually located at:
      `C:\Program Files\EqualizerAPO\config\`

2. **Download the Presets**:
    - Clone the repository or download the preset files directly from the GitHub repository.

    If you have Git installed, you can use:

    ```cmd
    git clone https://https://github.com/98Arvin/equalizer_apo
    ```

    If you do not have Git installed, you can download the repository as a ZIP file from GitHub and extract it to a location of your choice.

3. **Copy Presets to Config Folder**:
    - Navigate to the presets folder in your cloned repository or extracted ZIP file.
    - Copy the preset files to your Equalizer APO config folder. You can do this using Windows Explorer:

    **Using Windows Explorer:**
    - Open the folder where you downloaded/extracted the presets.
    - Select the preset files you want to copy.
    - Right-click and select `Copy`.
    - Navigate to `C:\Program Files\EqualizerAPO\config\`.
    - Right-click in the folder and select `Paste`.

4. **Load the Presets in Peace GUI**:
    - Open Peace GUI (a [user interface](https://sourceforge.net/projects/peace-equalizer-apo-extension/) for Equalizer APO).
    - Go to the `Presets` section.
    - Load the desired preset from the config folder.

**Contributing**
--------------

If you have suggestions for changes to existing presets, please feel free to open a pull request or issue. Include the following information with your suggestion:

* Headset model
* EQ settings (including frequency response data)
* Any relevant notes or comments about the preset
