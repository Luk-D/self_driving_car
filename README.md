
# Self-Driving Car
In this short project we aim to implement a self-driving car algorithm within a simulation environment. 

# How-To-Do
- Download the simulation environmnet from udacity [link](https://github.com/udacity/self-driving-car-sim "Link to GitHub")
- Follow these [instructions](https://github.com/udacity/CarND-Behavioral-Cloning-P3 "Link to Instructions")
![Game Menu](/img/game_menu.PNG)
![Game Racetrack](/img/game_racetrack.PNG)
- Self-training:
	- Start the simulation and record some data by the training mode (see picture) -> images and csv-file
	- Train the network with the train.py programm (perhaps a modifvation of the csv file is necessary)
- Or just use the given trained network by train - success.pth
- Start the autonomous mode and run the drive.py programm
- et voilà a self driving car

# To Be Considered
- Record a large amount of test data (best with a controller for smoother driving)
- Don't drive perfect (swerve about)
- The training for 10 epochs and a good amount of data lasts something about 45 min

# Some Facts
- Processing pipeline
![Pipeline](/img/pipeline.PNG)

- Network architecture
![Network](/img/network.PNG)

