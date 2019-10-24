this project, you will work with the Reacher environment (https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher)

    Set-up: Double-jointed arm which can move to target locations.
    Goal: The agents must move its hand to the goal location, and keep it there.
    Agents: The environment contains 10 agent linked to a single Brain.
    Agent Reward Function (independent):
        +0.1 Each step agent's hand is in goal location.
    Brains: One Brain with the following observation/action space.
        Vector Observation space: 26 variables corresponding to position, rotation, velocity, and angular velocities of the two arm Rigidbodies.
        Vector Action space: (Continuous) Size of 4, corresponding to torque applicable to two joints.
        Visual Observations: None.
    Reset Parameters: Five
        goal_size: radius of the goal zone
            Default: 5
            Recommended Minimum: 1
            Recommended Maximum: 10
        goal_speed: speed of the goal zone around the arm (in radians)
            Default: 1
            Recommended Minimum: 0.2
            Recommended Maximum: 4
        gravity
            Default: 9.81
            Recommended Minimum: 4
            Recommended Maximum: 20
        deviation: Magnitude of sinusoidal (cosine) deviation of the goal along the vertical dimension
            Default: 0
            Recommended Minimum: 0
            Recommended Maximum: 5
        deviation_freq: Frequency of the cosine deviation of the goal along the vertical dimension
            Default: 0
            Recommended Minimum: 0
            Recommended Maximum: 3
    Benchmark Mean Reward: 30



 Solve the Second Version

The barrier for solving the second version of the environment is slightly different, to take into account the presence of many agents. In particular, your agents must get an average score of +30 (over 100 consecutive episodes, and over all agents). Specifically,

    After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 20 (potentially different) scores. We then take the average of these 20 scores.
    This yields an average score for each episode (where the average is over all 20 agents).

The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.
Getting Started

    Download the environment from one of the links below. You need only select the environment that matches your operating system:

        Version 1: One (1) Agent
            Linux: click here
            Mac OSX: click here
            Windows (32-bit): click here
            Windows (64-bit): click here

        Version 2: Twenty (20) Agents
            Linux: click here
            Mac OSX: click here
            Windows (32-bit): click here
            Windows (64-bit): click here

    (For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link (version 1) or this link (version 2) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

    Place the file in the DRLND GitHub repository, in the p2_continuous-control/ folder, and unzip (or decompress) the file.

Instructions

Follow the instructions in Continuous_Control.ipynb to get started with training the agent!
