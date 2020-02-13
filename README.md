# NN-Model-for-ML-FLIGHT
This is a pre-trained Neural Network Model for the [ML Flight game by Immersive Limit](https://www.udemy.com/course/ai-flight/?referralCode=6F18F1CDA5C347908F52)

This model was trained as an experiment to help myself get a better grasp of the project.
The parameters used in the trainer_config.yaml file (which define parameters of our NN such as the number of hidden layers), 
are a little different from the ones suggested by the tutor. The race courses in the Training scene, also had slight changes from one another. This was done in hope of achieving better adaptability, and not getting a completely overfit model as a result. If you don't have time to train an NN yourself, or trying to troubleshoot, feel free to use this model in your project. 

## Result
The result is a model that performs really well on a course that closely resembles the original one. <b>
As a further experiment a boulder was placed right between two checkpoints(as shown below) in a way that didn't resemble any part of the tracks in the Training scene. Even though the agents tend to crash on it, usually at least one agent will overcome the object before crashing on it four times.
