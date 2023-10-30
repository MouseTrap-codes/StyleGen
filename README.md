# StyleGen
StyleGen is a machine learning training pipeline leveraging stable diffusion processes such as Dreambooth-LORA and Textual Inversion in order to allow users to create models that generate audio that mimics the style of a song but with minor changes through text commands, all done from Google Colab free-tier notebooks through optimization.

General-purpose code from latest version will be organized and uploaded November 4/5, for now demos from testing version 3 will be uploaded.

#V3 Demos (Using Textual Inversion)
The first demo will be the results of using StyleGen on 5 5-second snippets, converted to spectrograms, of "Loopster" by Kevin MacLeod to create new pieces of audio with a customized generative model fine-tuned to produce audio in the same style. 

The audio is converted to mp4 to make it playable from GitHub.

Original Song: 

https://github.com/MouseTrap42/StyleGen/assets/125787399/28a26d53-e902-449d-9179-a4db5320dabf

Dataset of 5 5-second snippets (512x512 spectrograms): 
https://drive.google.com/drive/folders/1cs7NJLqAzMjZhtDLfKmOA1lmQfhOrfqB?usp=share_link


StyleGen Outputs:

prompt: "<loopster_style>, quiet bass notes, peaceful ambience"

https://github.com/MouseTrap42/StyleGen/assets/125787399/3b860f93-79f3-4281-ab49-ee37f0bc49f2

prompt: "<loopster_style>, style electronica music_vibrant, synths and electric drums" 

https://github.com/MouseTrap42/StyleGen/assets/125787399/e38d9c36-8229-4d83-b85f-357031616f7a








