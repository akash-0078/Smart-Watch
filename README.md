
## Frequency-based Component Detection in Thermal Video

In this notebook, we'll explore how to detect components in a thermal video that have a specific frequency range, specifically 0-1 Hz. This task involves using computer vision techniques such as background subtraction, temporal filtering, and connected component analysis.

#### Objective:
Our objective is to identify and visualize components within the thermal video that exhibit a frequency of 0-1 Hz. These components are considered significant as they may represent objects or phenomena with slow periodic motion, which could be of interest in various applications such as surveillance, monitoring, or scientific research.

#### Methodology:

- **Background Subtraction:** We'll employ a background subtraction technique to isolate moving objects from the static background in the thermal video.

- **Temporal Filtering:** To reduce noise and smooth out the motion, we'll apply temporal filtering to the video frames.

- **Connected Component Analysis:** We'll perform connected component analysis on the foreground mask obtained from background subtraction to identify individual components.

- **Frequency Filtering:** Components will be filtered based on their frequency, calculated from their size, to retain only those within the desired range of 0-1 Hz.

- **Visualization:** Bounding boxes will be drawn around the identified components on the original video frames to visually represent their presence.

By following these steps, we aim to effectively detect and visualize components in the thermal video that exhibit the specified frequency range, enabling insights into the dynamics of the observed scene.