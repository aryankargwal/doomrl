# doomrl🔫
In the following repository we have implemented an RL agent in the Doom 1993. The game is a modern classic, pioneering the First Person Shooter genre, and we will be using our RL trained agent to traverse through some of the most difficult aspects of the game.
## Getting Started
As we start on the project there are a few things that we need to install and setup for our repository to work.
### Install Conda Env
``` conda env create -f environment.yml```
### VizDoom Installation
``` pip install vizdoom``` <br>
You can test whether the installation works by testing out the following [Python Notebook](vizdoom_demo.ipynb).
### Train First Basic Model
We are going to be wrapping VizDoom in OpenAI GYM and make an GYM Environment to train the models in.
## VizDoom
## Steps of Development
- [x] VizDoom Setup and Trials
- [ ] Convert Configuration Files into Gym Environment
- [ ] View Game State
- [ ] Setup CallBack
- [ ] Train Model
- [ ] Inference
