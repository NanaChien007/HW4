# in-class-activities
## Devlogs
### W1
when Moved the camera layer above the cat, the camera stopped following the cat as first person, but rather just sit in the same spot while the cat moves

https://nana-chien.itch.io/w1-in-class
### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

The r, g, b variables are floats because RGB value in Unity can contain decimals between 0.0 and 1.0, float let us store the decimal values while ints only store whole numbers.

_bounce variable is an int because it counts the number of times the ball bounces, they are all whole numbers so theres no need for decimal values

The error showed that the code was trying to use a double value with a float variable. Adding (0.1f) tells c# that the number should be treated as float
### W3
Activity 1
1. You’re building a visual novel, and you’re writing a method named GetResponse that gives you a character’s text response to a player’s dialogue choice. The relevant data for the dialogue choice are the player’s current friendship level with the character and a flag that tells you whether or not the player knows the character’s secret.
Input: bool
Output: string

2. You’re building a horror game, and you’re writing a method named SetLightDimness that makes the room’s lights brighter or darker based on the player’s current sanity level. The player’s sanity level is a number that goes from 0% - 100%. The method changes the light itself, so it doesn’t need any output.
Input: float
Out put: void

3. You’re building a rhythm game, and you’re writing a method named DidPlayerHitBeat that tells you whether or not the player accurately hit a beat based on the time that they pressed a key.
Input:bool
Output: float

Activity 2
A class could be described as a art palette, while the component is the paint the fills in the whole on the palette, and the variable would be the choose/mix of color 

Activity 3
Because the code is multiplying the ball's current color every time it bounces

### W4

The FloatAnimation script makes the fish food move up and down releatedly. The start () method sets the _timer to the value of _switchSpeed when the game begins. The Update () method runs every frame and controls the movement of the food. It uses the _up variable to determine which direction the food should move. When _up is true, the food moves upward, and when it's false, the food moves downward. The_timer decreases over time using Time.deltaTime, and once it reaches zero, it resets and switches the value of _up. This makes the food continously change directions and creates the floating animation. 

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
