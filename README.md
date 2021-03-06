# DLA Simulation
Simple diffusion limited aggregation simulation written in Python. Displays a live graphics window to the user with the specified window size, scale, and initial spacing.

## Example Output
<p align="center">
  <img src="https://i.imgur.com/gnBThAU.png"></img>
</p>

## How It Works
The program works by simulating each particle simultaneously. The starting particles are spaced according to the user's specifications (default every other pixel). Each particle does a "drunkard's walk" - randomly choosing to move up, down, left, right, or stay in place. If a particle sticks to a "stuck" particle, it becomes stuck itself, and stops wandering. Upon initialization there is only one "stuck" particle in the center of the plane. 

## Dependencies and How to Install Them
The only dependency is <a href = "https://bitbucket.org/pyglet/pyglet/wiki/Download"> pyglet. </a> Instructions for installation can be found on pyglet's website.
