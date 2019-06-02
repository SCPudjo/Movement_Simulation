# Movement_AI

Demonstration of various Movement AI

![Movement AI Demo](resources/demo.gif)
### Requirements:

You must install Python and the Pygame module to run this simulaton.
Install Pygame with the following command:

    pip install pygame
    
Execute World.py to start

### Current Movements:

Idle: Creature will idle and do nothing

Wander: Creatures will wander in random directions while also avoiding collision

Boid Flocking: Simulation of the flocking behaviour of birds. 
Based on the artificial life program developed by Craig Reynolds. 
An example of emergent behaviour arising from a simple set of rules:
    
    Separation: steer to avoid crowding local flockmates
    Alignment: steer towards the average heading of local flockmates
    Cohesion: steer to move towards the average position (center of mass) of local flockmates
    
Targeted Movement: Creatures will move towards a target (place with T)
   
Stealth: Creatures will hide behind obstacles from Predators (WIP)
    
### Controls:

    1: Set behaviour to Idle    
    2: Set behaviour to Wander    
    3: Set behaviour to Boid Flocking
    4: Set behaviour to Targeted Movement
    4: Set behaviour to Stealth
    
    S: Spawn a pair of creatures
    P: Spawn a predator (WIP)
    T: Place target
    Z: Reset simulation
    
    Keypad 1-4,6-9: Spawn a wall
    Keypad 5: Spawn a pillar
    O: Remove all walls
    
    SPACE: Pause simulation
