# StyleGen
StyleGen is a machine learning training pipeline leveraging stable diffusion processes such as Dreambooth-LORA and Textual Inversion in order to allow users to create models that generate audio that mimics the style of a song but with minor changes through text commands, all done from Google Colab free-tier notebooks through optimization.

#V2 Demos (Using Dreambooth-LoRA) (Yielded best results as of now) 
The first demo will be the results of using StyleGen on 5 5-second snippets, converted to spectrograms, of "Loopster" by Kevin MacLeod to create new pieces of audio with a customized generative model fine-tuned to produce audio in the same style. 

The audio is converted to mp4 to make it playable from GitHub.

Original Song: 

https://github.com/MouseTrap42/StyleGen/assets/125787399/28a26d53-e902-449d-9179-a4db5320dabf

5 second snippet from Original Song:

https://github.com/MouseTrap42/StyleGen/assets/125787399/0bad326d-8fa9-4984-82c6-ee915b74ad75



Dataset of 5 5-second snippets (512x512 spectrograms): 

https://drive.google.com/drive/folders/1cs7NJLqAzMjZhtDLfKmOA1lmQfhOrfqB?usp=share_link



Output from general-purpose text-to-audio model (Riffusion):

prompt: "create an energetic and catchy tune that makes people want to get up and dance, incorporating lively rhythms and an uplifting melody" 


https://github.com/MouseTrap42/StyleGen/assets/125787399/d5ba94b2-3405-4eb2-b0e1-34288a52bd7c


StyleGen Outputs:

StyleGen v2 (Dreambooth-LoRA, best result thus far):

prompt: "Loopster style, create an energetic and catchy tune that makes people want to get up and dance, incorporating lively rhythms and an uplifting melody" 

https://github.com/MouseTrap42/StyleGen/assets/125787399/2239c052-d777-48f1-9f88-63773585bb26



StyleGen v3 (Textual Inversion, inferior result):

prompt: "<loopster_style>, create an energetic and catchy tune that makes people want to get up and dance, incorporating lively rhythms and an uplifting melody"

https://github.com/MouseTrap42/StyleGen/assets/125787399/6fba26ba-65d0-4fe2-aa42-ea24a8b55c68










