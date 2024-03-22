Simulation of the Biological process of Transcription and visualization with a 2d graphic representation as well as multiple dynamic graphs.
Developed by the Bioinformatician Christos Botos.
Written in both Python and C.

**Versions**
[Botos_DNA_Transcription_Simulation_v0.6] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.6)
[Botos_DNA_Transcription_Simulation_v0.5] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.5)
[Botos_DNA_Transcription_Simulation_v0.4] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.4)
[Botos_DNA_Transcription_Simulation_v0.3] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.3)
[Botos_DNA_Transcription_Simulation_v0.2] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.2)
[Botos_DNA_Transcription_Simulation_v0.1] (https://github.com/ChrisBotos/Botos_DNA_Transcription_Simulation_v0.1)

**Possible Uses**
The code is designed to be easy to read and manipulate to your situation. 
For example there is already a class "obstacles.py" that you can use for any point where an RNA pol may pause.
You can use this to create your own kind of pause site, for example we added lesions(DNA damage areas) see how lesions where implemented for inspiration.

Another use could be to play around with the parameters of the simulation and also utalize the dynamic graphs library we developed for pygame to visualize the effects.
These produced graphs and the arrays they come form could also possibly be used in a machine learning model that would try to change the parameters of the simulation so that those graphs match the ones we get in the lab.
