# VoiceCloning

I am sorry for the inconvenience but I wasn't able to upload large files on GitHub that's why I have used Google Drive.

I have Implemented 2 versions of Voice Cloner, the first one using SV2TTS and second one using TorToise TTS.

# I have uploaded the outputs, models and demo videos of both the versions on Google Drive:- https://drive.google.com/drive/folders/1GFbnzay_ZITPchtusix9Pdy6djtTptgZ?usp=sharing

# Version 1 - VOICE CLONING using SV2TTS
   For Detailed installation use the below Github link.
   Github Link:= [https://github.com/CorentinJ/Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning#real-time-voice-cloning)

   ![Screenshot 2023-07-19 135659](https://github.com/KuNNaL2412/VoiceCloning/assets/94506399/619a54ae-4721-4855-8779-a2c7ec5feba6)

1. Install Requirements
   Both Windows and Linux are supported. A GPU is recommended for training and for inference speed, but is not mandatory.

   Python 3.7 is recommended. Python 3.5 or greater should work, but you'll probably have to tweak the dependencies' versions. I recommend setting up a virtual environment using venv, but this is optional.

   Install ffmpeg. This is necessary for reading audio files.

   Install PyTorch. Pick the latest stable version, your operating system, your package manager (pip by default) and finally pick any of the proposed CUDA versions if you have a GPU, otherwise pick CPU. Run the given command.

   Install the remaining requirements with pip install -r requirements.txt

2. (Optional) Download Pretrained Models
   Pretrained models are now downloaded automatically.

3. (Optional) Test Configuration
   Before you download any dataset, you can begin by testing your configuration with:

   python demo_cli.py

   If all tests pass, you're good to go.

4. (Optional) Download Datasets
   For playing with the toolbox alone, I only recommend downloading LibriSpeech/train-clean-100. Extract the contents as <datasets_root>/LibriSpeech/train-clean-100 where <datasets_root> is a directory of your choosing. Other datasets are supported in the toolbox, see here. You're free not to download any dataset, but then you will need your own data as audio files or you will have to record it with the toolbox.

5. Launch the Toolbox
   
   You can then try the toolbox:

   python demo_toolbox.py -d <datasets_root>

   or

   python demo_toolbox.py

EVALUATION OF THE MODEL:

The evaluation of the model is done on the basis of:-  

Generalized End-To-End Loss for Speaker Verification (GE2E) Embedding Output: 

![Screenshot 2023-07-19 135726](https://github.com/KuNNaL2412/VoiceCloning/assets/94506399/158e2a77-caf4-483d-bc51-ea2e6f40388f)

Mel Spectrogram:

![Screenshot 2023-07-19 135742](https://github.com/KuNNaL2412/VoiceCloning/assets/94506399/903eff8c-5f57-4eb7-8c6f-92542a22acdf)

and Cluster Formation for input and output voices: where a dot determines an input and a cross determines an output.

![Screenshot 2023-07-19 135759](https://github.com/KuNNaL2412/VoiceCloning/assets/94506399/1fc45c52-6c71-4c44-876d-c4c7aa2a396b)


# Version 2 - VOICE CLONING using TorToise TTS

   To run the model you just have to run the Google Colab Notebook



***NOTE: DUE TO THE LIMITATION OF MY LAPTOP's HARDWARE, I WAS NOT ABLE TO TRAIN AND IMPLEMENT THE PROJECTS PROPERLY***
