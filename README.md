- 👋 Hi, I’m @dylan-roberts-capstone-2021
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

# Langton's Ant
Langton's Ant is a simulation that takes place on a grid of squares and is a results of a small, simple ruleset that causes the "ant" to move. The ant
has an orientation, a location on the grid, and each square can be either white or filled (for mine I used blue). Here is a short summary of the rules:
If the ant is on a white square, then the ant moves 90 degrees clockwise, flips the color of the that square, and moves one square forward.
If the ant is on a black square, then the ant moves 90 degrees *counter-clockwise*, flips the color of the square, and move forward 1 square.
This simple ruleset causes the ant to move around in a seemingly random manner, creating a mess of squares in its trail. However this pattern has no
element of randomness, so the pattern is the same each time that the simulation runs. At around 11,000 movements, there is a very peculier formation that
occurs. The ant gets almost "stuck" in a loop of movement. This creates a so-called "staircase".
