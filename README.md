# Breakout_AI_OpenAI-Gym

## OpenAI Gym Setup guide

### Installation guide
Follow the instructions [here](https://gym.openai.com/docs/) for OpenAI Gym installations.

You'll also need [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [pip](https://pip.pypa.io/en/stable/installing).

Next, install these dependencies:
```shell
pip install neat-python==0.8 argparse scipy
```
### Running the program
There are some arguements:

`--max-steps` : The maximum number of steps to take per genome

`--episodes` : The number of times to run a single genome

`--render` : Renders the game

`--generations` : The number of generations

`--checkpoint` : Use a checkpoint to start the simulation

`--num-cores` : The number of cores to use

To run, execute this on your terminal or command prompt:

```shell
python Breakout_AI.py --max-steps YOUR_OPTION --episodes YOUR_OPTION --generations YOUR_OPTION --render
```
