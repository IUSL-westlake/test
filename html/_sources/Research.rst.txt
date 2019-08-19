Research
=========

Affine formation maneuver control of multi-agent systems
A multi-agent formation control task is usually constituted by two control problems:

  * Formation shape control is to steer a group of mobile agents starting from a given initial configuration to form a desired geometric pattern.
  * Formation maneuver control is to steer the mobile agents to maneuver as a whole such that the centroid, orientation, scale, and even shape of the formation can be changed continuously. Formation maneuver control is important for the formation to respond dynamically to the environment to achieve, for example, obstacle avoidance.

We solve the two problems by proposing a leader-follower affine formation control strategy based on stress matrices. With the proposed control laws, not only the desired formation pattern can be achieved, any time-varying affine transformation such as a translation, rotation, scaling, or even shape deformation of the formation can be tracked. The desired formation maneuvers are only accessible to the leaders. The proposed control laws are all globally stable and can be implemented in each agent's local reference frame.

.. raw:: html

  <iframe width="560" height="315" src="https://www.youtube.com/embed/HyCn8r7LBZw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/G7pI6EaW2oI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
