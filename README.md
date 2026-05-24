**publishDate**: 2026-05-24

**title**: DODO – Speech Assistant Toy for Speech Disabled Kids

**excerpt**: DODO is an interactive speech therapy toy designed to assist children with speech disabilities through real-time speech recognition, multisensory feedback, and engaging therapy activities.

**tags**:

Speech Therapy
Embedded AI
ESP32
MYOSA Sensors
Assistive Technology

Making speech therapy interactive, engaging, and accessible for children through AI-enabled assistive technology.

##Acknowledgements

We sincerely thank Team MYOSA Sensors for providing the MYOSA development platform, sensor modules, and technical guidance throughout the project development process.

We also express our gratitude to our mentor, faculty members, and teammates for their continuous support and valuable suggestions during the implementation of this project.

##Overview

Traditional speech therapy sessions for children can become repetitive and difficult to sustain for long durations. To improve engagement and participation, we developed DODO, an AI-powered interactive speech assistant toy designed specifically for speech-disabled children.

The system integrates an ESP32-based MYOSA board, speech recognition using Edge Impulse, sensor-based interaction, and multisensory feedback mechanisms to create an enjoyable therapy experience.

DODO listens to the child’s pronunciation, analyzes speech patterns in real time, and responds with visual, audio, and physical feedback when words are pronounced correctly. The toy includes vocabulary and phonics practice modes, helping children improve speech clarity, confidence, and communication skills.

##Key Features  
1. Oral Motor Training  
​Gamified blowing exercises help children strengthen their cheek and oral muscles for clearer speech.
 
​2. Focus & Stability Tracking  
​Interactive balance challenges prompt children to keep the toy steady, building physical concentration.

​3. Smart Speech Recognition  
​An offline AI companion listens to the child's voice to provide instant pronunciation feedback. 

​4. Touchless Hand Gestures  
​Simple hand waves allow children to easily switch practice words or express basic needs.  

​5. Multi-Sensory Rewards  
​Correct words instantly trigger a playful buzzer, screen celebrations, and happy physical movements. 

​6. Parent-to-Child Autonomy  
​The design transitions easily from parent-guided learning to independent child self-practice.  

##Demo/Examples
<img width="1919" height="800" alt="Screenshot 2026-03-27 123523" src="https://github.com/user-attachments/assets/fff4808b-0864-43bb-9289-b3cdee06ac13" />
_Figure 1:Spectrogram Created Using Samples The first stage of the pipeline involves feature extraction. Raw audio samples are processed into a spectrogram, which represents the frequency content of the sound over time. This visual representation helps the model identify unique "audio signatures" associated with different speech patterns.

<img width="814" height="708" alt="Screenshot 2026-03-27 123706" src="https://github.com/user-attachments/assets/8e741fb7-6a53-4b49-908d-904138d6ffa3" />
_Figure2:The U-Map visualization provides a graphical representation of the entire dataset. It clusters similar data points together, allowing the team to verify that the collected samples are distinct and that there is a clear separation between different classes (e.g., specific words vs. background noise).


 
