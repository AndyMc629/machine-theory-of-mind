# machine-theory-of-mind
This repo contains the code and technical documentation for a project between a few people (see 'People') whose aim is to reproduce and add to the study in the [Machine Theory of Mind](https://arxiv.org/pdf/1802.07740.pdf) paper from DeepMind.

## Technologies
The DeepMind implementation doesn't mention specific technologies used, so I have made the following selection (subject to change as the project develops)

- Python
- Tensorflow
- Google Colab 
- OpenAI Gym (for at least simple agents and worlds)

## Repository Structure
There are a few pieces to this project so I suggest the repo will be structured roughly like this [example](https://drivendata.github.io/cookiecutter-data-science/). Note this will be added to as the project progresses and should by no means be considered complete.

```bash
|-- README.md
|-- notebooks 
|-- docs
|-- data
    |-- gridworld
    |-- agents
|-- models
    |-- character_nets
    |-- mental_nets
    |-- prediction_nets
|-- src
    |-- __init__.py
    |-- simulation
         |-- __init__.py
         |-- gridworld
         |-- agents
            |-- random
            |-- 
    |-- data
         |-- __init__.py
         |-- preprocess
            |-- spatconc.py (perform spatialisation concatenation, take actions from sims and tile over space to create appropriate traj's)
 
```

## Workflow
Will use a worklflow and set up like that suggested [here](https://zerowithdot.com/colab-github-workflow/).

## Related Resources

- [Blog post](https://www.google.co.uk/amp/s/pillowlab.wordpress.com/2019/01/28/machine-theory-of-mind/amp/) on Machine Theory of Mind 

- [Advanced Deep Learning and Reinforcement Learning DeepMind](https://github.com/Zhenye-Na/advanced-deep-learning-and-reinforcement-learning-deepmind)

- [World Models](https://worldmodels.github.io)

- [DeepMind Research](https://github.com/deepmind/deepmind-research) repository 

## People
Collaborators on the technical implementation side of the project

- [Andy McMahon](https://www.linkedin.com/in/andymcmahon629/)
- Sofia Jativa (FHI, University College London)
- [Stuart Armstrong](https://www.fhi.ox.ac.uk/team/stuart-armstrong/) (FHI, University of Oxford)
