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

<p align="center">
  <img src="https://github.com/user-attachments/assets/371e1fa5-06f4-4c3b-8b19-0a075c66d82b" />
 width="800"><br/>
  <i>Your image caption</i>
</p>
<img width="1919" height="800" alt="Screenshot 2026-03-27 123523" src="https://github.com/user-attachments/assets/fff4808b-0864-43bb-9289-b3cdee06ac13" />
_Figure 1:Spectrogram Created Using Samples The first stage of the pipeline involves feature extraction. Raw audio samples are processed into a spectrogram, which represents the frequency content of the sound over time. This visual representation helps the model identify unique "audio signatures" associated with different speech patterns.

<img width="814" height="708" alt="Screenshot 2026-03-27 123706" src="https://github.com/user-attachments/assets/4751a110-ae80-42a2-93af-f7cb514a27aa" />
_Figure 2:The U-Map visualization provides a graphical representation of the entire dataset. It clusters similar data points together, allowing the team to verify that the collected samples are distinct and that there is a clear separation between different classes (e.g., specific words vs. background noise).

<img width="1656" height="669" alt="Screenshot 2026-03-27 123739" src="https://github.com/user-attachments/assets/cf19034d-844a-4c5c-8ab1-aacd50ebaad0" />
_Figure 3:Arduino library created using trained model.

##Features Detailed

1. Multi-Sensory Oral Motor Training  
​The toy utilizes a high-precision BMP180 pressure sensor to create gamified breathing exercises (like blowing out a digital candle). This physical interaction directly helps children strengthen their cheek and oral muscles, which are foundational for clear speech articulation.  

​2. Physical Stability & Focus Tracking  
​Using the MPU6050 inertial measurement unit (IMU), the toy monitors physical movement and tilt. It turns concentration into a game by challenging children—especially those with short attention spans or hyperactivity—to keep the toy steady and calm before moving to the next task.  

​3. Edge AI Speech Recognition  
​Powered by an ESP32-WROOM processor and a custom-trained Edge Impulse Machine Learning model, the toy processes voice commands locally in real-time via the INMP441 digital microphone. It accurately checks the child's pronunciation of target words (like "Cat") without requiring an active internet connection.  

​4. Interactive, Touchless Navigation  
​Integrating the APDS-9960 gesture sensor allows children to interact with the device using touchless hand movements. Kids can wave their hands left or right to switch between practice words, or trigger communication shortcuts, making the interface highly accessible and engaging.  

​5. Instant Multi-Tiered Reward System  
​To reinforce correct pronunciation and boost confidence, the toy provides instant, joyful feedback. When a child says a word correctly, the system simultaneously sounds a playful buzzer, displays a success message on the OLED screen, and activates a Servo motor to make the toy physically wave or move.  

​6. Progressive Autonomy (Parent-to-Child Hand-Off)  
​The toy's workflow is thoughtfully designed to adapt to a child’s comfort level. It begins as a collaborative tool for parents and children to use together, but features intuitive visual prompts and simple sensor triggers that allow the child to eventually transition to completely independent self-practice.  




 
