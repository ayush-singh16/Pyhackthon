
# Hackathon_232VMTHR0415
---
## This is my solution for PyHackthon hosted by Jain Online :

## Task : Home Voice Assistance 

### Features --> 
  * Voice Activity Detection (VAD) :
  * Instead of using a VAD model / voice classification model , I implemented a simple VAD .
  * It replies on only "Assistant" yu can change it as well.

  #### Speech to Text (STT):
  * I employed Speech recognization library .
  * I can also use streamlit_mic_recorder .

  #### LLM : 
  * So for the inference im using Groq (llama model) for the home voice commands. 

  #### Text to Speech (TTS):
  * I'm using Coqui/your_TTS model which is a light weight model for TTS .
  * it can also do voice cloning .

---
### Future Work -->
  * Realtime Avatar Talking .
  * Optimzed models for STT / VAD / TTS like faster_whisper , Bark , silerio etc 
  * Optimzed for Edge Devices .
  * Will use LLM model which is trained on home commands. 
---
## INFERENCE-->
  * Just run the cells one by one from the ipynb file
  * ngrok api key 
  * Groqcloud api key 

https://github.com/user-attachments/assets/187fdab4-a151-4c50-9799-d2abd556842f
