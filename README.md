https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/Measurement_visualization_compressed.mp4
# Quantum Jargon Busters

## Abstract

This lecture is designed to introduce Gate based quantum computing in an intuitive manner to high school students with a major in physics. No preknowledge in quantum mechanics is needed.
On our path from superficial buzz words to the main goal, comprehending the quantum teleportation channel we will debunk quantum myths, get to know fun facts and learn about the basic gates.
We hope to create an awareness about the true power of quantum computation.
The skills and knowledge aquired in this lecture will help students interested in quantum technologies to further engage the quantum computing community and allow them to follow more advanced lectures regarding this topic.
This lecture aims to provide as much information about quantum computing as possible using minmial mathematical and physical concepts. We therefore e.g. neglect the normalization and phase of the wavefunction to make this lecture more
tangible to high school students. Solutions to all the exercises are provided in the [exercises](https://github.com/steppony/Qiskit-Hackaton/tree/main/Exercises) folder.


### Kahoot
A [Kahoot](https://create.kahoot.it/details/3c621705-3a35-43ba-8eb9-cf678dfda3b7) quiz is used to open and accompany the lecture along its way. It is used to introduce a short break in between the different sections of the lectures keeping the students enganged and recatch their attention. 
Hence making the lecture more interactive and fun. Only a few questions will be asked at a time with the last one acting as a transition to the next section. The questions cover actual facts about buzzwords regarding quantum computers as well as myths and can be a bit more andvanced. The lecturer will give a short explaination of the true statement after the question was asked in the Kahoot.
This procedure will reveal myths that are untrue or partly unture while new facts will have a learning effect aswell or spark interest in a specific topic. 
Examples are: 
	
	Q: Quantum Computing can only be realized by a gate based approach. 
	A: False. There are different realizations of a quantum computer such as measurement based or adiabatic quantum quantum computing.
	Q: A quantum system will collapse only if you observe it.
	A: False. Also interactions with the envoirnment and noise can force a quantum wavefunction to collapse. We will investigate how measurements affect our quantum system in the next section. 


To start the lecture a picture of a science fiction teleportation will be presented asking the students what is happening in the picture. With the answer being teleporation the next question is if teleporation is actually possible in real life. 
Regardless of the outcome next the quantum teleporation cirucit is shown. The students are told that at the end of the lecture they will at least know parts of this circuit. They are also told that along their learing curve they will get to know more fun facts such as the teleportation one.


### Introduction

Duration: 5 Minutes

Form of Teaching: Presentation by Teacher

Content:

- Introduction with Kahoot *Questions 1-3*
- Teleportation Circuit![TELEPORTATION CIRCUIT](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/teleportation_circuit.png)
- The Teleportation circuit is used to show the students where the lecture is headed and what the students can expect to learn.
### Qubits & Superposition 

Duration: 15 Minutes

Form of Teaching: Teaching 

Content:
- Kahoot *Questions 4-8* 
- Explain what a qubit is in distinction to classical bit
- Focus the concept of superposition with the 2D animation of the "Bloch circle" !["Bloch circle"](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/qubit_animation.gif)
- Compare exponential scale up of qubit states due to superpostion to linear scale up of bits

Takeaway:

- Quantum computers process information differently since superposition allows for quantum parallelism 

### Gates and measurements 

Duration: 25 Minutes

Form of Teaching: Open Discussion & Exercices + Video

- Kahoot *Questions 9-10*
- X-,H-Gate with [Learning exercise](https://github.com/steppony/Qiskit-Hackaton/blob/main/Exercises/learning_exercises.ipynb) part a),b)
- Visiualization and explanation of X-,H- & Z-Gate with the single-qubit gate truth tables ![single-qubit](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/single_qubit_gates.png) 
- Explaining the concept of two-qubit controlled gates with the two-qubit controlled gate truth tables![two-qubit controlled](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/multiple_qubit_gates.png) 
- Experiencing the CX-Gate in the [Learning exercise](https://github.com/steppony/Qiskit-Hackaton/blob/main/Exercises/learning_exercises.ipynb) part c)
- (BONUS) Intuitivley get in touch with the concept of entanglement by combining single-,two-qubit gates as well as measurements with the [CX-H-X excercise](https://github.com/steppony/Qiskit-Hackaton/blob/main/Exercises/CX_H_X_excercise.ipynb)
- Show the self explaining video ([link to video](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/Measurement_visualization_cut.mp4)) to quantum measurements (the corresponding slides are shown below) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-1.png) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-2.png) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-3.png) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-4.png) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-5.png) ![pdf](https://github.com/steppony/Qiskit-Hackaton/blob/main/Visualizations/measurement_visualization-6.png) 

Takeway: 
- Know the basic sinlge-qubit gates and their action to different states
- Transfer single-qubit knowledge to two-qubit controlled gates


### Putting it all together - Quantum teleportation


Duration: 15 Minutes

Form of Teaching: Teacher explains qiskit code


Content: 
- Kahoot *questions 11-13*
- Step by step walk through the quantum [teleportation code](https://github.com/steppony/Qiskit-Hackaton/blob/main/Exercises/test_exercise.ipynb)
- Demonstrate that teleporting a quantum state actually works

Takeaway:

- A complicated quantum circuit is build out of subsystems which are easy to understand



### Testing Exercise

Homework
 - [Superdense coding](https://github.com/steppony/Qiskit-Hackaton/blob/main/Exercises/test_exercise.ipynb) exercise with instructions to do at home

Takeaway:
- Be confident to tackle other quantum circuits

# Qiskit-Hackaton Excersices
The tasks done by us can be found in the [Hackathon_Excersices](https://github.com/steppony/Qiskit-Hackaton/tree/main/hackathon_exercises) folder.



