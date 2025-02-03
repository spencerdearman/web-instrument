# **[HarmonyGrid](https://spencerdearman.github.io/harmony-grid/)**

<img width="1261" alt="Screenshot 2025-02-02 at 5 25 42 PM" src="https://github.com/user-attachments/assets/0371e75f-31c5-4940-9b15-5397c64be593" />

**HarmonyGrid** is an interactive instrument that transforms colors detected by your camera into dynamic musical notes. By dividing the camera feed into a grid, HarmonyGrid maps colors and brightness levels to musical notes, creating a unique soundscape.

---

## **Features**
1. **Dynamic Note Generation**  
   - Colors detected from the camera feed are mapped to musical notes based on preset color-to-note relationships.
   - Brighter colors produce **louder, more intense notes**, while darker colors result in softer sounds.

2. **Grid-Based Detection**  
   - The video feed is divided into a grid of customizable size (1x1 to 6x6).  
   - Each grid section averages the colors, playing multiple notes simultaneously for richer harmonies.

3. **Real-Time Adjustments**  
   - Use the **grid size slider** to dynamically control the grid resolution:
     - **1x1** for a single averaged note.  
     - **6x6** for a complex blend of 36 notes.  

4. **Interactive Effects**  
   - Toggle on/off audio effects like:
     - **Reverb** – Adds depth and ambiance.  
     - **Phaser** – Creates sweeping sound effects.  
     - **Vibrato** – Adds pitch modulations.

5. **Simple User Interface**  
   - Start the camera with a single button click.  
   - Adjust grid size and toggle effects seamlessly through intuitive controls.

---

## **How It Works**

1. **Camera Activation**  
   - Click the **"Allow Camera"** button to enable your camera feed.  
   - HarmonyGrid will automatically start detecting colors from the video stream.

2. **Color-to-Note Mapping**  
   - Each detected color is mapped to a set of musical notes:
     - **Red → C Notes**
     - **Orange → D Notes**
     - **Yellow → E Notes**
     - **Green → F Notes**
     - **Blue → A Notes**
     - **Purple → B Notes**

3. **Grid Size and Note Intensity**  
   - The grid size determines how many notes are played per frame:
     - Smaller grids = Simpler melodies.  
     - Larger grids = Complex, layered harmonies.  
   - Brightness levels (calculated using the luminance formula) scale note intensity (velocity), making brighter areas sound louder.

4. **Audio Effects**  
   - Toggle effects like **Reverb**, **Phaser**, and **Vibrato** to customize the sound.

---

## **Controls**

| **Control**            | **Description**                                                      |
|-------------------------|----------------------------------------------------------------------|
| **Allow Camera**        | Activates the camera feed for color detection.                      |
| **Grid Size Slider**    | Adjusts the resolution of the grid (1x1 to 6x6).                    |
| **Start/Stop Button**   | Toggles the audio playback on or off.                               |
| **Toggle Reverb**       | Adds or removes reverb for ambient sound.                           |
| **Toggle Phaser**       | Adds sweeping, phase-shifting sound effects.                       |
| **Toggle Vibrato**      | Adds pitch modulation to the generated notes.                       |

---
